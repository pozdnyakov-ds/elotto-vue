<template>
  <app-header></app-header>
  <div>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </div>

  <RouterView />
</template>

<script>
  import { RouterLink, RouterView } from 'vue-router'
  import AppHeader from './components/AppHeader.vue'

  export default {
    components: {
      AppHeader
    }
  }
</script>

<style>
@import '@/assets/css/style.css';
@import '@/assets/css/elotto.css';

#app {
  min-width: 100%;
  margin: 0;
  font-weight: normal;
}

a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

</style>
