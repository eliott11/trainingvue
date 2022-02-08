<template>
  <section class="stats">
    <h4>Outcome Statistics</h4>

    <div class="stats-all">

      <div class="stats-shopping">
        <div><i class="bi bi-cart"></i></div>
        <div>
          <div>Progression</div>
          <div class="shopping-title">Shopping</div>
        </div>
        <div class="stats-%">52%</div>
      </div>

      <div class="stats-electro">
        <div><i class="bi bi-truck"></i></div>
        <div>
          <div>Progression</div>
          <div class="electro-title">Electronics</div>
        </div>
        <div class="stats-%">21%</div>
      </div>

      <div class="stats-travels">
        <div><i class="fas fa-plane"></i></div>
        <div>
          <div>Progression</div>
          <div class="travels-title">Travels</div>
        </div>
        <div class="stats-%">74%</div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: 'Stats',
  props: {
    
  }
}
</script>

<style scoped>
.stats-shopping, .stats-electro, .stats-travels {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
}
/* .shopping-title , .electro-title, .travels-title {
  float: left;
} */
.stats-\% {
  color: #696969;
}
.bi-cart, .bi-truck, .fa-plane {
  box-shadow: 0px 16px 24px rgba(0, 0, 0, 0.06), 0px 2px 6px rgba(0, 0, 0, 0.04), 0px 0px 1px rgba(0, 0, 0, 0.04);
  border-radius: 3px;
  padding: 8px;
}
.bi-cart {
  background: #FFEADA;
  color: #F8964C;
}
.bi-truck {
  background: #DDF9E4;
  color: #22A447;
}
.fa-plane {
  background: #E4F0FF;
  color: #70A6E8;
}
</style>
