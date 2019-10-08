<template>
  <nav id="nav">
    <router-link to="/">Home</router-link>
    <router-link :to="{ name: 'brazil' }">Brazil</router-link>
    <router-link :to="{ name: 'panama' }">Panama</router-link>
    <router-link :to="{ name: 'jamaica' }">Jamaica</router-link>
    <router-link :to="{ name: 'hawaii' }">Hawaii</router-link>
  </nav>
</template>
<script>
export default {
  name: "TheNavigation"
};
</script>
<style scoped>
#nav a {
  margin: 0 5px;
}

#nav a.active {
  color: teal;
}
</style>
