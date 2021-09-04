<template>
    <div id="app">
        <NavBar />
        <nuxt />
    </div>
</template>

<script>
import NavBar from '~/components/NavBar.vue';

export default {
    components: {
        NavBar,
    }
}
</script>

<style>
html {
  box-sizing: border-box;
}

*,
*::before,
*::after {
  box-sizing: border-box;
  margin: 0;
}
</style>