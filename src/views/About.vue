<template>
  <h3>Version 1.0.0</h3>
  <h3>
    Created By:
    <a class="name-link" href="https://www.jordanmasone.com/" target="_blank"
      >Jordan Masone</a
    >
  </h3>
  <router-link to="/">Go Back</router-link>
</template>

<script>
export default {
  name: "About",
};
</script>

<style scoped>
.name-link {
  font-size: inherit;
  text-decoration: none;
  cursor: pointer;
  color: green;
}
.name-link:hover {
  color: steelblue;
}
</style>