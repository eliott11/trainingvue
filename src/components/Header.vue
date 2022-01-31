<template>
  <section class="header">
    <div>
      <h3>Weekly sumup</h3>
      <h6>Get summary of your weekly online transactions here.</h6>
    </div>
    <div class="headMenu">
      <i class="bi bi-envelope-fill"></i>
      <i class="bi bi-bell-fill"></i>
      <i></i>
      <div>
        <p>Eliott</p>
        <p>Admin Account</p>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'Header',
  props: {}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

section {
  font-family: "Dongle";
  display: flex;
}
h3 {
  font-size: 5.5rem;
  font-weight: 800;
  margin: 0 auto;
}
h6 {
  font-size: 2.5rem;
  font-weight: lighter;
  margin: 0 auto;
}
h6, div i, div p {
  color: #C7C7C7;
}
p {
  margin: 0 auto;
}
.headMenu {
  display: flex;
  justify-content: flex-end;
  align-items: center;
}
</style>
