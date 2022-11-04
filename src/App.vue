<script setup lang="ts">
import { RouterLink, RouterView, useRouter } from 'vue-router'

useRouter().push({ name: 'home' });
</script>

<template>
   <header>
      <nav>
         <RouterLink to="/">Home</RouterLink> |
         <RouterLink to="/about">About</RouterLink>
      </nav>
   </header>
   <main>
      <RouterView />
   </main>
</template>
