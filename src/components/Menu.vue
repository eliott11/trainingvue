<template>
    <section id="menu">
        <div class="headernav">
          <div class="cloudlogo">
            <img src="../assets/cloudlogo.png">
          </div>
          <div class="titlelogo">cloudcash</div>
        </div>
        <ul>
            <li><img src=""><a href="">Overview</a></li>
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

.headernav {
  display: flex;
}
.cloudlogo {
  display: flex;
  align-items: center;
}
.titlelogo {
  font-weight: bolder;
  color: #0f4366;
  font: 1.7rem "Dongle";
}
img {
  width: 40px;
  height: auto;
  display: flex;
  margin: 8px;
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
