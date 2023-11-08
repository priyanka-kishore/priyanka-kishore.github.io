<template>
  <header>
    <div>
      <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
        <RouterLink to="/skills">Skills</RouterLink>
        <RouterLink to="/work">Work</RouterLink>
        <RouterLink to="/find-me">Find Me</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>
<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>
<style scoped></style>
