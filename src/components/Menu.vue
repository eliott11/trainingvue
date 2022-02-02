<template>
    <section id="menu">
        <div class="menu__topnav">
            <div class="headernav">
            <div class="cloudlogo">
              <img src="../assets/cloudlogo.png">
            </div>
            <div class="titlelogo">cloudcash</div>
        </div>
        <ul class="menu__navmenu">
            <li><i class="bi bi-graph-up"></i><a href="">Overview</a></li>
            <li><i class="bi bi-list-ul"></i><a href="">Transactions</a></li>
            <li><i class="bi bi-credit-card"></i><a href="">Cards</a></li>
            <li><i class="bi bi-file-earmark"></i><a href="">Invoices</a></li>
            <li><i class="bi bi-bookmark-star"></i><a href="">Goals</a></li>
            <li><i class="bi bi-gear"></i><a href="">Settings</a></li>
        </ul>
        </div>
        <div class="menu__navdescription">
            <svg xmlns="http://www.w3.org/2000/svg" width="64" height="64" fill="#0786db" class="bi bi-cloud-upload" viewBox="0 0 16 16">
            <path fill-rule="evenodd" d="M4.406 1.342A5.53 5.53 0 0 1 8 0c2.69 0 4.923 2 5.166 4.579C14.758 4.804 16 6.137 16 7.773 16 9.569 14.502 11 12.687 11H10a.5.5 0 0 1 0-1h2.688C13.979 10 15 8.988 15 7.773c0-1.216-1.02-2.228-2.313-2.228h-.5v-.5C12.188 2.825 10.328 1 8 1a4.53 4.53 0 0 0-2.941 1.1c-.757.652-1.153 1.438-1.153 2.055v.448l-.445.049C2.064 4.805 1 5.952 1 7.318 1 8.785 2.23 10 3.781 10H6a.5.5 0 0 1 0 1H3.781C1.708 11 0 9.366 0 7.318c0-1.763 1.266-3.223 2.942-3.593.143-.863.698-1.723 1.464-2.383z"/>
            <path fill-rule="evenodd" d="M7.646 4.146a.5.5 0 0 1 .708 0l3 3a.5.5 0 0 1-.708.708L8.5 5.707V14.5a.5.5 0 0 1-1 0V5.707L5.354 7.854a.5.5 0 1 1-.708-.708l3-3z"/>
            </svg>
            <p>Give your money<br />awesome space in cloud</p>
            <button>Upgrade to premium <i class="bi bi-arrow-up-circle"></i></button>
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
#menu {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  font-family: "Dongle";
  width: 270px;
  height: calc(100vh - 46px);
  padding: 25px 0 20px 0;
  border-right: solid 2px #c7c7c7;
}
.menu__topnav {
  display: flex;
  flex-direction: column;
}
.headernav {
  display: flex;
  justify-content: center;
  margin-bottom: 30px;
}
.cloudlogo {
  display: flex;
  align-items: center;
  margin: 5px;
}
.titlelogo {
  font-weight: bolder;
  color: #0f4366;
  font-size: 1.8rem;
}
.cloudlogo img {
  height: 25px;
  display: flex;
}
.menu__navmenu {
  color: #C7C7C7;
  font-size: 1.5rem;
}
ul {
  list-style-type: none;
  padding: 10px 0px 0px 0px;
  margin: 0 auto;
}
li {
  list-style-type: none;
  list-style-position: outside;
  margin: 5px 10px 0px 10px;
  display: flex;
}
li i {
  margin-right: 15px;
}
.bi-graph-up, .bi-list-ul, .bi-credit-card, .bi-file-earmark, .bi-bookmark-star, .bi-gear {
  display: flex;
  align-items: center;
}
a {
  color: #C7C7C7;
  text-decoration:none;
}
.menu__navdescription {
  text-align: center;
}
.menu__navdescription p {
  font-size: 1em;
  margin-block-start: -5px;
  margin-block-end: 10px;
  line-height: 0.7em;
}
.menu__navdescription button {
  background-color: #FFC145;
  color: #404040;
  padding: 10px;
  font-size: 0.8em;
  border: 2px solid #FFC145;
  border-radius: 14px;
  transition-duration: 0.2s;
  padding: 10px 10px;
}
.menu__navdescription button:hover {
  background-color: white;
  color: #FFC145;
  border: 2px solid #FFC145;
}
</style>