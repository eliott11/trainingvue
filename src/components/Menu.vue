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
            <svg xmlns="http://www.w3.org/2000/svg" width="82" height="82" fill="grey" class="bi bi-cloud-upload" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M4.406 1.342A5.53 5.53 0 0 1 8 0c2.69 0 4.923 2 5.166 4.579C14.758 4.804 16 6.137 16 7.773 16 9.569 14.502 11 12.687 11H10a.5.5 0 0 1 0-1h2.688C13.979 10 15 8.988 15 7.773c0-1.216-1.02-2.228-2.313-2.228h-.5v-.5C12.188 2.825 10.328 1 8 1a4.53 4.53 0 0 0-2.941 1.1c-.757.652-1.153 1.438-1.153 2.055v.448l-.445.049C2.064 4.805 1 5.952 1 7.318 1 8.785 2.23 10 3.781 10H6a.5.5 0 0 1 0 1H3.781C1.708 11 0 9.366 0 7.318c0-1.763 1.266-3.223 2.942-3.593.143-.863.698-1.723 1.464-2.383z"/>
            <path fill-rule="evenodd" d="M7.646 4.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L8.5 5.707V14.5a.5.5 0 0 1-1 0V5.707L5.354 7.854a.5.5 0 1 1-.708-.708l3-3z"/>
            </svg>
            <p>Give your money<br />awesome space in cloud</p>
            <button class="btnNav">Upgrade to premium <i class="bi bi-arrow-up-circle"></i></button>
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
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: "Dongle";
  width: 300px;
  justify-content: left;
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
  font-size: 2.5rem;
}
.cloudlogo img {
  height: 25px;
  display: flex;
  
}
ul {
  list-style-type: none;
  padding: 10px 10px 0px 10px; /*haut droite bas gauche*/
  margin: 0 auto;
}
li {
  list-style-type: none;
  list-style-position: outside;
  margin-top: 25px;
  margin-bottom: 25px;
}
li i {
  margin-right: 15px;
}
a {
  color: #C7C7C7;
  text-decoration:none;
}
.navmenu {
  color: #C7C7C7;
  font-size: 2.3rem;
}
.navdescription {
  text-align: center;
}
.navdescription p {
  font-size: 1.5em;
}
.navdescription button {
  background-color: #FFC145;
  color: #404040;
  padding: 10px;
  font-size: 20px;
  border: 2px solid #FFC145;
  border-radius: 14px;
  transition-duration: 0.2s;
  padding: 15px 32px;
}
.navdescription button:hover {
  background-color: white;
  color: #FFC145;
  border: 2px solid #FFC145;
}
</style>
