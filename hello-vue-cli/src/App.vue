<script>
import Profile from './components/Profile.vue';
import Education from './components/Education.vue';
import Skills from './components/Skills.vue';

export default {
  name: 'app',
  components: {
    Profile,
    Education,
    Skills,
    }
  };

</script>

<template>
  <div class = "app-container">
    <Profile />
    <Education />
    <Skills />
  </div>
</template>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
