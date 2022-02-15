<template>
  <section class="pricing">
        <h4>Goals</h4>
        <div class="goals-content"> <!--- class generale --->
            <div class="holiday block-shadow"> <!--- general class card --->
                <div class="price-stats"> <!--- card content top--->
                    <span class="price-text">$550</span>
                    <span class="date-text">12/20/20</span>
                </div>
                <div> <!--- card content bottom--->
                    <div><i class="fa fa-mountain"></i></div>
                    <div class="name-stats">Holidays</div>
                </div>
            </div>
            <div class="renovation block-shadow"> <!--- general class card --->
                <div class="price-stats"> <!--- card content top--->
                    <span class="price-text">$200</span>
                    <span class="date-text">12/20/20</span>
                </div>
                <div> <!--- card content bottom--->
                    <div><i class="fa fa-brush"></i></div>
                    <div class="name-stats">Rent</div>
                </div>
            </div>
            <div class="game block-shadow"> <!--- general class card --->
                <div class="price-stats"> <!--- card content top--->
                    <span class="price-text">$820</span>
                    <span class="date-text">12/20/20</span>
                </div>
                <div> <!--- card content bottom--->
                    <div><i class="bi bi-controller"></i></div>
                    <div class="name-stats">Games</div>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'Pricing',
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.goals-content { /* cards general display */
    display: flex;
    justify-content: space-between;
    height: 145px;
}
.holiday, .renovation, .game { /* cards display content */
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 33%;
}
.price-stats { /* price */
    color: #696969;
    display: flex;
    flex-direction: column;
}
span { /* text general */
    margin: -5px 0;
}
.price-text { /* price text */
    font-weight: 600;
    font-size: 20px;
    margin: 0;
}
.date-text { /* date text */
    color: #AEAEAE;
    font-size: 14px;
}
.fa-mountain, .fa-brush, .bi-controller { /* icons size */
    font-size: 24px;
}
.fa-mountain {          /* icons color */
    color: #6DA2E4;
}
.fa-brush {
    color: #F17F29;
}
.bi-controller {
    color: #1E9540;
}
.name-stats {
    color: #404040;
}
</style>
