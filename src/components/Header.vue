<template>
  <section class="header">
    <div>
      <h3>Weekly sumup</h3>
      <h6>Get summary of your weekly online transactions here.</h6>
    </div>
    <div class="headmenu">
      <div class="headmenu__icons">
        <i class="bi bi-envelope-fill" fill="#0786db"></i>
        <i class="bi bi-bell-fill"></i>
        <i class="bi bi-person-circle"></i>
      </div>
      <div>
        <p class="username"><b>Eliott</b></p>
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
  padding: 0;
  justify-content: space-between;
}
h3 {
  
  margin: 0 auto;
  color: #404040;
  line-height: 115%;
  font-family: Suprema;
  font-style: normal;
  font-weight: 600;
  font-size: 43.3726px;
  line-height: 53px;
}
h6 {
  /* font-size: 2rem;
  font-weight:lighter; */
  margin: 0 auto;
  color: #AEAEAE;
  font-family: Suprema;
  font-style: normal;
  font-weight: normal;
  font-size: 16.0564px;
  line-height: 20px;
}
div.headmenu__icons {
  display: flex;
  align-items: center;
  justify-content: center;
}
.bi-envelope-fill, .bi-bell-fill {
  font-size: 1.4rem;
  margin-right: 20px;
}
.bi-person-circle {
  font-size: 2rem;
  margin-right: 10px;
  color: #FFC145;
}
.bi-envelope-fill, .bi-bell-fill, .bi-person-circle {
  display: flex;
  align-items: center;
}
.username {
  color: black;
}
p {
  margin: 0 auto;
  font-weight: lighter;
  line-height: 90%;
}
.headmenu {
  display: flex;
  align-items: center;
  color: #c7c7c7;
}
</style>
