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
        { id: 1, name: 'Minimal Bedroom' },
        { id: 2, name: 'Classic Minimal Bedroom' },
        { id: 3, name: 'Minimal Bedroom table' },
        { id: 4, name: 'Modern Medroom' },
        { id: 5, name: 'Minimal Bedroom' },
        { id: 6, name: 'Modern Bedroom' },
        { id: 7, name: 'System Table' },
        { id: 8, name: 'Modern Bedroom' }
      ],
    };
  },
};
</script>