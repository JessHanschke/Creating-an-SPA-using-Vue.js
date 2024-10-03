<template> 
    <div id="profile" class="profile">
      <div class="row no-gutters">
        <div class="col-md-4 profile-left">
          <img src="/src/assets/jess.jpg" class="profile-img" alt="Profile Photo" />
          <div class="profile-details">
            <h3 class="job-title">Web Developer</h3>
            <p class="contact-info">Contact: 0917 657 4170</p>
            <p class="email">
              <a href="mailto:jessicahanschke@gmail.com">jessicahanschke@gmail.com</a>
            </p>
          </div>
        </div>
  
        <div class="col-md-8 profile-right">
          <h1>Profile</h1>
          <h2 class="profile-name">{{ name }}</h2>
          <p><strong>Objective:</strong> {{ objective }}</p>
          <p><strong>Course:</strong> {{ course }}</p>
          <p><strong>Specialization:</strong> {{ specialization }}</p>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        objective: 'To excel in web development and build impactful digital solutions.',
        name: 'Jessica Soriano Hanschke',
        course: 'Bachelor in Science in Information Technology Major in Web Development',
        specialization: 'Front-end Development & UI/UX Design',
      };
    },
  };
  </script>
  
  <style scoped>
.profile {
  margin: 30px 0;
  padding: 20px;
  background-color: #f8f9fa;
  border-radius: 15px;
  margin-bottom: 0; 
}
  .profile-left {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
  }
  
  .profile-img {
    width: 170px;
    height: 170px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 10px;
    border: 4px solid #8B0000;
  }
  
  .job-title {
    font-size: 1.5rem;
    color: black;
    text-align: center;
    margin-bottom: 10px;
  }
  
  .contact-info,
  .email {
    font-size: 1rem;
    text-align: center;
    margin-bottom: 3px;
  }
  
  .email a {
    color: #8B0000;
    text-decoration: none;
  }
  
  .email a:hover {
    text-decoration: underline;
  }
  
  .profile-right {
    display: flex;
    flex-direction: column;
    justify-content: center;
    padding: 20px;
  }
  
  .profile-name {
    font-size: 2rem;
    font-weight: bold;
    color: #8B0000;
    margin-bottom: 10px;
  }
  
  h1 {
    font-size: 1.6rem;
    line-height: 1.5;
    margin-bottom: 10px;
  }
  
  p {
    font-size: 1.1rem;
    line-height: 1.5;
    margin-bottom: 10px;
  }
  
  p strong {
    color: #710c04;
  }
  
  .profile-line {
    width: 100%;
    height: 2px;
    background-color: #8B0000;
    margin: 50px 0;
  }
  
  .row {
    display: flex;
    align-items: flex-start;
  }
  
  .col-md-4 {
    text-align: center;
  }
  
  .col-md-8 {
    padding-left: 30px;
  }
  
  @media (max-width: 768px) {
    .row {
      flex-direction: column;
    }
    .col-md-8 {
      padding-left: 0;
    }
  }
  </style>
  