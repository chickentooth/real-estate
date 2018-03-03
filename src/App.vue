<template>
  <div id="app" class="index-page sidebar-collapse">
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
