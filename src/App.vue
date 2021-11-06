
<template>
  <div id="app" class="container">
    <div class="row py-4">
      <project-cv />
      <br>
      <br>
      <project-cvv />
    </div>
  </div>
</template>

<script>
  import ProjectCv from './components/ProjectCv.vue';
  import ProjectCvv from './components/ProjectCvv.vue';

  export default {
    name: 'app',
    components: {
      ProjectCv,
      ProjectCvv
      }
    }
</script>
