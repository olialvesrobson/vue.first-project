<script setup>
  import Dashboard from './components/dashboard/Dashboard.vue'
  import MainVue from './components/project/Main.vue';
 
</script>

<template>
  <header>
    <div class="wrapper">
      <Dashboard/>
    </div>
  </header>
  <main>
    <div class="app">
      <MainVue />
    </div>
  </main>
</template>

<style>
  @import './assets/base.css';

  #app {
    max-width: 1280px;
    margin: 0 auto;
    padding: 2rem;

    font-weight: normal;
  }

  header {
    line-height: 1.5;
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

  @media (min-width: 1024px) {
    body {
      display: flex;
      place-items: center;
    }

    #app {
      display: grid;
      grid-template-columns: 1fr 1fr;
      padding: 0 2rem;
    }

    header {
      display: flex;
      place-items: center;
      padding-right: calc(var(--section-gap) / 2);
    }

    header .wrapper {
      display: flex;
      place-items: flex-start;
      flex-wrap: wrap;
    }

  }
</style>
