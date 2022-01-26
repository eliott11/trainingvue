<template>
    <section id="menu">
        <div class="headernav">
          <div class="cloudlogo">
            <img src="../assets/cloudlogo.png">
          </div>
          <div class="titlelogo">cloudcash</div>
        </div>
        <ul class="navmenu">
            <li><i class="bi bi-graph-up"></i><a href="">Overview</a></li>
            <li><i class="bi bi-list-ul"></i><a href="">Transactions</a></li>
            <li><i class="bi bi-credit-card"></i><a href="">Cards</a></li>
            <li><i class="bi bi-file-earmark"></i><a href="">Invoices</a></li>
            <li><i class="bi bi-bookmark-star"></i><a href="">Goals</a></li>
            <li><i class="bi bi-gear"></i><a href="">Settings</a></li>
        </ul>
        <div class="navdescription">
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
section {
  display: inline-block;
  margin: 40px;
}
.headernav {
  display: flex;
}
.cloudlogo {
  display: flex;
  align-items: center;
  margin: 5px;
}
.titlelogo {
  font-weight: bolder;
  color: #0f4366;
  font: 3rem "Dongle";
}
.cloudlogo img {
  height: 30px;
  display: flex;
  
}
ul {
  list-style-type: none;
  padding: 10px 10px 0px 10px; /*haut droite bas gauche*/
  display: inline-block;
  margin: 0 auto;
}
li {
    list-style-type: none;
    list-style-position: outside;
    margin-top: 25px;
    margin-bottom: 25px;
    padding-bottom: -25px;
}
i {
  margin-right: 15px;
}
a {
    color: #C7C7C7;
    text-decoration:none;
}
.navmenu {
  color: #C7C7C7;
  font: 2em "Dongle";
}
.navdescription {
  text-align: center;
}
</style>
