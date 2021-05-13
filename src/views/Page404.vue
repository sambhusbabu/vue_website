<template>
  <div>
    <md-empty-state
      md-icon="broken_image"
      md-label="404"
      md-description="Page Not Found">
      <router-link to="/"><md-button class="md-primary md-raised"> Home </md-button></router-link>
    </md-empty-state>
  </div>
</template>

<script>
  export default {
    name: 'EmptyStateBasic'
  }
</script>
