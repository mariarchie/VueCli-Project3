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
        { id: 11, name: 'Minimal Bathroom' },
        { id: 12, name: 'Classic Minimal Bathroom' },
        { id: 13, name: 'Minimal Bathroom table' },
        { id: 14, name: 'Modern Bathroom' },
        { id: 15, name: 'System Table' },
        { id: 16, name: 'Modern Bathroom' }
      ],
    };
  },
};
</script>