<template>
    <div id="skills" class="skills">
      <div class="skills-line"></div>
      <h2 class="section-title">Skills</h2>
      <div class="skills-details">
        <div class="skills-item">
          <strong>Training:</strong>
          <div class="skill-name">{{ trainings[0] }}</div>
          <div class="skill-name">{{ trainings[1] }}</div>
          <div class="skill-name">{{ trainings[2] }}</div>
        </div>
        <div class="skills-item">
          <strong>Seminars:</strong>
          <div class="skill-name">{{ seminars[0] }}</div>
          <div class="skill-name">{{ seminars[1] }}</div>
          <div class="skill-name">{{ seminars[2] }}</div>
        </div>
        <div class="skills-item">
          <strong>Technologies:</strong>
          <div class="skill-name">{{ technologies[0] }}</div>
          <div class="skill-name">{{ technologies[1] }}</div>
          <div class="skill-name">{{ technologies[2] }}</div>
          <div class="skill-name">{{ technologies[3] }}</div>
          <div class="skill-name">{{ technologies[4] }}</div>
        </div>
        <div class="skills-item">
          <strong>Programming Languages:</strong>
          <div class="skill-name">{{ programmingLanguages[0] }}</div>
          <div class="skill-name">{{ programmingLanguages[1] }}</div>
          <div class="skill-name">{{ programmingLanguages[2] }}</div>
          <div class="skill-name">{{ programmingLanguages[3] }}</div>
          <div class="skill-name">{{ programmingLanguages[4] }}</div>
        </div>
        <div class="skills-line"></div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        trainings: ['Web Development Bootcamp', 'UI/UX Design Certification','CompTIA Certification'],
        seminars: ['InteREACTive UI: A Frontend Development Workshop', 'Flutter Workshop','GitHub Workshop'],
        technologies: ['HTML5', 'CSS3', 'JavaScript', 'Bootstrap', 'Vue.js'],
        programmingLanguages: ['JavaScript', 'Python', 'PHP', 'HTML', 'CSS'],
      };
    },
  };
  </script>
  
  <style scoped>
  .skills {
    margin: 10px 0;
    padding: 20px;
    background-color: #f8f9fa;
    border-radius: 15px;
  }
  
  .skills-line {
    width: 100%;
    height: 2px;
    background-color: #8B0000;
    margin-top: 0; 
  }
  
  .section-title {
    font-size: 1.5rem;
    color: black;
    margin-bottom: 20px;
    margin-bottom: 0; 
  }
  
  .skills-details {
    margin: 20px 0;
  }
  
  .skills-item {
    font-size: 1.2rem;
    line-height: 1.6;
    margin-bottom: 15px;
  }
  
  .skill-name {
    margin-left: 20px;
    font-style: italic;
  }
  
  @media (max-width: 768px) {
    .section-title {
      font-size: 1.5rem;
    }
  
    .skills-item {
      font-size: 1rem;
    }
  }
  </style>
  