<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import axios from 'axios'
axios.get('https://www.baidu.com')
    .then((response: { data: any; }) => {
        console.log(response.data)
    })
    .catch((error: any) => {
        console.log(error)
    })
</script>

<template>
  <header>
      <div class="wrapper">
          <nav>
              <RouterLink to="/">Op</RouterLink>
              <RouterLink to="/image">Jsk</RouterLink>
              <RouterLink to="/image">Sk</RouterLink>
              <RouterLink to="/image">内搭</RouterLink>
              <RouterLink to="/image">外搭</RouterLink>
          </nav>
      </div>
  </header>

    <RouterView />
</template>
