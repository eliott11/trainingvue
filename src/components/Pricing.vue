<template>
  <section class="pricing">
        <h4>Goals</h4>
        <div class="goals-content">
            <div class="holiday block-shadow">
                <div>
                    <div>Price $</div>
                    <div>Date</div>
                </div>
                <div>
                    <div>Logo</div>
                    <div>Holidays</div>
                </div>
            </div>
            <div class="renovation block-shadow">
                <div>
                    <div>Price $</div>
                    <div>Date</div>
                </div>
                <div>
                    <div>Logo</div>
                    <div>Rent</div>
                </div>
            </div>
            <div class="game block-shadow">
                <div>
                    <div>Price $</div>
                    <div>Date</div>
                </div>
                <div>
                    <div>Logo</div>
                    <div>Games</div>
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
}
.holiday, .renovation, .game {
    display: flex;
    flex-direction: column;
    width: 33%;
}
</style>
