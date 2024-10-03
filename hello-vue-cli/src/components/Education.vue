<template> 
    <div id="education" class="education">
    <div class="education-line"></div>
      <h2 class="section-title">Education</h2>
      <div class="education-details">
        <div class="education-item">
          <strong>Elementary:</strong>
          <div class="school-name">{{ elementary }}</div>
        </div>
        <div class="education-item">
          <strong>Junior High School:</strong>
          <div class="school-name">{{ juniorHigh }}</div>
        </div>
        <div class="education-item">
          <strong>Senior High School:</strong>
          <div class="school-name">{{ seniorHigh }}</div>
        </div>
        <div class="education-item">
          <strong>College:</strong>
          <div class="school-name">{{ college }}</div>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
    data() {
      return {
        elementary: 'Achievers Special Education Center',
        juniorHigh: 'Holy Family Academy',
        seniorHigh: 'Holy Family Academy',
        college: 'Holy Angel University',
      };
    },
  };
  </script>
  
  <style scoped>
 .education {
  margin: 10px 0;
  padding: 20px;
  background-color: #f8f9fa;
  border-radius: 15px;
  text-align: left;
  margin-top: 0;
}
  
  .section-title {
    font-size: 1.5rem;
    color: black;
    margin-bottom: 20px;
  }
  
  .education-details {
    margin: 20px 0;
  }
  
  .education-line {
    width: 100%;
    height: 2px;
    background-color: #8B0000;
    margin: 10px 0;
  }
  
  .education-item {
    font-size: 1.2rem;
    line-height: 1.6;
    margin-bottom: 15px;
    padding-left: 20px;
    position: relative;
  }
  
  .education-item:before {
    content: '✦ ';
    color: #8B0000;
    font-weight: bold;
    position: absolute;
    left: 0;
  }
  
  .school-name {
    margin-left: 20px;
    font-style: italic;
  }
  
  @media (max-width: 768px) {
    .section-title {
      font-size: 1.5rem;
    }
  
    .education-item {
      font-size: 1rem;
    }
  }
  </style>
  