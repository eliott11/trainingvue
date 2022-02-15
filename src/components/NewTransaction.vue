<template>
  <section class="newtran">
    <div class="newtrans-section"> <!--- general --->
      <div class="transcontent-left block-shadow"> <!--- content left --->
        <h4>New Transaction</h4>
        <div class="content-top"> <!--- general img + name --->
          <div class="user-transac"> <!--- img + name --->
            <div class=photo><img src="../assets/1.jpg"></div>
            <div>Ann</div>
          </div>
          <div class="user-transac"> <!--- img + name --->
            <div class=photo><img src="../assets/2.jpg"></div>
            <div>Monica</div>
          </div>
          <div class="user-transac"> <!--- img + name --->
            <div class=photo><img src="../assets/3.jpg"></div>
            <div>John</div>
          </div>
          <div class="user-transac"> <!--- img + name --->
            <div class=photo><img src="../assets/4.jpg"></div>
            <div>Mike</div>
          </div>
          <div class="user-transac"> <!--- img + name --->
            <div class=photo><img src="../assets/5.jpg"></div>
            <div>Mia</div>
          </div>
          <div class="user-transac"> <!--- icon + description --->
            <div class=photo><i class="bi bi-plus-circle-fill"></i></div>
            <div>Add New</div>
          </div>
        </div>
        <div class="btn-bottom"> <!--- button bottom --->
            <input type="$">
            <button>Send the transfert <b>></b></button>
        </div>
      </div>
      <div class="transcontent-right"> <!--- content right --->
          <div class="right-btn">
            <div><i class="fab fa-bitcoin btc2"></i></div>
            <div><i class="fab fa-bitcoin btc1"></i></div>
            <div class="text-btn-right">Get great<br>loan! ></div>
          </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'NewTransaction',
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.newtrans-section { /* content section */
  display: flex;
  color: #404040;
  justify-content: space-between;
}
.transcontent-left { /* content left */
  width: 70%;
}
.transcontent-right { /* content right */
  width: 30%;
}
.content-top { /* content top */
  display: flex;
  font-size: 15px;
}
.photo { /* image div */
  text-align: center;
}
.photo img { /* image size */
  height: 25px;
}
.user-transac { /* card user margin */
  margin: 7px;
}
.bi { /* icon + */
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-content: center;
  margin: 5.2px;
  font-size: 15px;
  color: #FFC145;
}
.btn-bottom { /* button bottom space between */
  display: flex;
  justify-content: space-between;
}
input, button { /* button height */
  height: 40px;
}
input { /* input display */
  border: 1px solid #197BBD;
  box-sizing: border-box;
  border-radius: 8px;
  width: 60%;
}
button { /* button display */
  background: #FFC145;
  border-radius: 13.617px;
  border: none;
  font-size: 11.1442px;
  line-height: 14px;
  font-weight: bold;
  color: #404040;
}
.right-btn { /* right part button */
  background: #ED654C;
  box-shadow: 0px 0px 50px rgba(0, 0, 0, 0.05);
  border-radius: 19.0044px;
  height: 100%;
  font-size: 18px;
  position: relative;

}
.text-btn-right { /* text right button */
  position: absolute;
  bottom: 5px;
  margin-left: 10px;
  color: #ffffff;
  font-weight: bold;
}
.fa-bitcoin { /* icons background general*/
  font-size: 27px;
  color: #D15842;
}
.btc1 { /* icon */
  position: absolute;
  transform: rotate(-35deg);
  margin: 50px 0 0 45px;
}
.btc2 { /* icon */
  position: absolute;
  transform: rotate(20deg);
  margin: 75px 0 0 5px;
}
</style>
