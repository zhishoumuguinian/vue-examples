<template>
  <div id="app">
    <sidebar />
    <div id="routerview">
      <router-view v-bind:key="$route.path" />
    </div>
    <alertdialog />
  </div>
</template>
<script>
export default {
  components: {
    sidebar: () => import("@/views/Sidebar"),
    alertdialog: () => import("@/components/AlertDialog")
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 20px;
}
#routerview {
  vertical-align: top;
  border: 2px solid red;
  display: inline-block;
}
</style>
