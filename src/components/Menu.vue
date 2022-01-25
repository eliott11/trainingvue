<template>
    <section id="menu">
        <div class="logotitle">
          <div class="cloudlogo">
            <img src="../assets/cloudlogo.png">
          </div>
          <div><h3>cloudcash</h3></div>
        </div>
        <ul>
            <li><img src="" alt=""><a href="">Overview</a></li>
            <li><a href="">Transactions</a></li>
            <li><a href="">Cards</a></li>
            <li><a href="">Invoices</a></li>
            <li><a href="">Goals</a></li>
            <li><a href="">Settings</a></li>
        </ul>
        <div>
            <p>Give your money<br />awesome space in cloud</p>
            <button>Upgrade to premium</button>
        </div>
    </section>  
</template>

<script>
export default {
  name: "Menu",
  props: {},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

.logotitle {
  display: flex;
}
.cloudlogo {
  display: flex;
  align-items: center;
}
img {
  width: 45px;
  height: auto;
  display: flex;
}
ul {
  list-style-type: none;
  padding: 10px 20px 0px 10px; /*haut droite bas gauche*/
  display: inline-block;
  margin: 0 auto;
}
li {
    list-style-type: none;
    list-style-position: outside;
}
a {
    color: #CCCCCC;
    text-decoration:none;
}

</style>
