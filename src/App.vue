<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
    import navbar from './components/template/navbar.vue'
export default {
  name: 'App',
    components: {
        navbar
    },
}
</script>
