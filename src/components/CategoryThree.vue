<template>
  <div>
    <ul class="projects-container center">
      <li class="project" v-for="project in projects" :key="project.id">{{ project.name }}</li>
    </ul>
  </div>
</template>
  
<script>
export default {
  data() {
    return {
      projects: [
        { id: 31, name: 'Minimal Kitchen' },
        { id: 32, name: 'Classic Minimal Kitchen' },
        { id: 33, name: 'Minimal Kitchen table' },
        { id: 34, name: 'Modern Kitchen' },
        { id: 35, name: 'Minimal Kitchen' },
        { id: 36, name: 'Modern Kitchen' },
        { id: 37, name: 'Modern Kitchen' }
      ],
    };
  },
};
</script>