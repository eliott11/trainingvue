<template>
  <section class="header">
    <div>
      <h3>Weekly sumup</h3>
      <h6>Get summary of your weekly online transactions here.</h6>
    </div>
    <div class="headMenu">
      <i class="bi bi-envelope-fill" fill="#0786db"></i>
      <i class="bi bi-bell-fill"></i>
      <i class="bi bi-person-circle"></i>
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
.header {
  font-family: "Dongle";
  display: flex;
  align-items: center;
  position: relative;
  justify-content: space-between;
  padding: 0 10px;
}
h3 {
  font-size: 66px;
  font-weight: normal;
  margin: -10px 0;
  color: #404040;
}
h6 {
  font-size: 2rem;
  font-weight: lighter;
  margin: 0 auto;
}
h6, div i, div p {
  color: #C7C7C7;
}
i .bi-person-circle {
  color: rgb(19, 171, 241);
}
i {
  margin-right: 20px;
}
p {
  margin: 0 auto;
}
.headMenu {
  display: flex;
  align-items: center;
}
</style>
