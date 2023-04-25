<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <nav>
        <RouterLink to="/">七的衣柜</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>