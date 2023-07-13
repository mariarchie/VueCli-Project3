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
        { id: 41, name: 'Minimal Livingroom'},
        { id: 42, name: 'Classic Minimal Livingroom' },
        { id: 43, name: 'Minimal Livingroom table' },
        { id: 44, name: 'Modern Livingroom' },
        { id: 45, name: 'Minimal Livingroom' },
        { id: 46, name: 'Modern Livingroom' },
        { id: 47, name: 'System Table' },
        { id: 48, name: 'Modern Livingroom' }
      ],
    };
  },
};
</script>