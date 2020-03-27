<template>
  <div id="app">
    <CalendarWeek />
    <CalendarEntry />
  </div>
</template>

<script>
  import CalendarWeek from "./components/CalendarWeek";
  import CalendarEntry from "./components/CalendarEntry";
  export default {
    name: 'App',
    components: {CalendarEntry, CalendarWeek}
  }
</script>

<style lang="scss">
  html,body {
    height: 100%;
  }
  #app {}
  #calender-week {}
  #calender-entry {}
</style>

<style lang="scss" scoped>
  #app {
    height: inherit;
    background-color: #e6e6e6;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }
</style>
