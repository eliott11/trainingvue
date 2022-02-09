<template>
  <section class="pricing">
        <h4>Goals</h4>
        <div class="goals-content">
            <div class="holiday block-shadow">
                <div class="price-stats">
                    <div>Price $</div>
                    <div>12/20/20</div>
                </div>
                <div>
                    <div><i class="fa fa-mountain"></i></div>
                    <div class="name-stats">Holidays</div>
                </div>
            </div>
            <div class="renovation block-shadow">
                <div class="price-stats">
                    <div>Price $</div>
                    <div>12/20/20</div>
                </div>
                <div>
                    <div><i class="fa fa-brush"></i></div>
                    <div class="name-stats">Rent</div>
                </div>
            </div>
            <div class="game block-shadow">
                <div class="price-stats">
                    <div>Price $</div>
                    <div>12/20/20</div>
                </div>
                <div>
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
.goals-content {
    display: flex;
    justify-content: space-between;
    height: 145px;
}
.holiday, .renovation, .game {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    width: 33%;
}
.price-stats {
    color: #696969;
}
.fa-mountain, .fa-brush, .bi-controller {
    font-size: 24px;
}
.fa-mountain {
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
