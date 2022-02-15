<template>
    <section id="menu">
        <div class="menu__topnav"> <!--- top menu + list --->
            <div class="headernav"> <!--- top menu --->
            <div class="cloudlogo"> <!--- logo menu --->
              <img src="../assets/cloudlogo.png">
            </div>
            <div class="titlelogo">cloudcash</div>
        </div>
        <ul class="menu__navmenu"> <!--- list menu --->
            <li><i class="bi bi-graph-up"></i><a href="">Overview</a></li>
            <li><i class="bi bi-list-ul"></i><a href="">Transactions</a></li>
            <li><i class="bi bi-credit-card"></i><a href="">Cards</a></li>
            <li><i class="bi bi-file-earmark"></i><a href="">Invoices</a></li>
            <li><i class="bi bi-bookmark-star"></i><a href="">Goals</a></li>
            <li><i class="bi bi-gear"></i><a href="">Settings</a></li>
        </ul>
        </div>
        <div class="menu__navdescription"> <!--- bottom menu --->
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
#menu { /* menu */
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: 220px;
  height: 100vh;
  padding: 25px 0 20px 0;
  border-right: solid 2px #EBEBEB;
}
.menu__topnav { /* menu top + list display */
  display: flex;
  flex-direction: column;
}
.headernav { /* top menu display */
  display: flex;
  justify-content: center;
  margin-bottom: 30px;
}
.cloudlogo { /* logo menu */
  display: flex;
  align-items: center;
  margin: 5px;
}
.cloudlogo img { /* logo img */
  height: 25px;
  display: flex;
}
.titlelogo { /* title logo */
font-style:normal;
font-weight: bold;
font-size: 16.7475px;
line-height: 21px;
display: flex;
align-self: center;
color: #0F4264;
}
.menu__navmenu { /* menu */
  color: #C7C7C7;
  font-family: Suprema;
  font-style: normal;
  font-weight: 500;
  line-height: 25px;
}
ul { /* list ul */
  list-style-type: none;
  padding: 10px 0px 0px 0px;
  margin: 0 auto;
}
li { /* list li */
  margin: 5px 10px 0px 10px;
  display: flex;
}
li i { /* list li i */
  margin-right: 15px;
}
.bi-graph-up, .bi-list-ul, .bi-credit-card, .bi-file-earmark, .bi-bookmark-star, .bi-gear { /* icons */
  display: flex;
  align-items: center;
}
a { /* menu title section */
  color: #C7C7C7;
  text-decoration:none;
}
.menu__navdescription { /* center bottom menu */
  text-align: center;
}
.menu__navdescription p { /* bottom menu display */
  margin-block-start: -5px;
  margin-block-end: 10px;
  font-style: normal;
  font-weight: normal;
  font-size: 8.7511px;
  line-height: 11px;
}
.menu__navdescription button { /* bottom menu button */
  background-color: #FFC145;
  color: #404040;
  padding: 10px;
  font-size: 0.8em;
  border: 2px solid #FFC145;
  border-radius: 13.617px;
  transition-duration: 0.2s;
  padding: 10px 10px;
}
.menu__navdescription button:hover { /* bottom menu button effect */
  background-color: white;
  color: #FFC145;
  border: 2px solid #FFC145;
}
</style>