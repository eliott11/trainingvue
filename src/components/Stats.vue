<template>
  <section class="stats">
    <h4>Outcome Statistics</h4>

    <div class="stats-all">

      <div class="stats-shopping">
        <div><i class="bi bi-cart"></i></div>
        <div class="mt-2 mb-2">
          <div class="progress mb-1">
            <div class="progress-bar-shopping" role="progressbar" aria-valuenow="52" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          <div class="shopping-title">Shopping</div>
        </div>
        <div class="stats-%">52%</div>
      </div>

      <div class="stats-electro">
        <div><i class="bi bi-truck"></i></div>
        <div class="mt-2 mb-2">
          <div class="progress mb-1">
            <div class="progress-bar-electro" role="progressbar" aria-valuenow="21" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
          <div class="electro-title">Electronics</div>
        </div>
        <div class="stats-%">21%</div>
      </div>

      <div class="stats-travels">
        <div><i class="fas fa-plane"></i></div>
        <div class="mt-2 mb-2">
          <div class="progress  mb-1">
            <div class="progress-bar-travels" role="progressbar" aria-valuenow="74" aria-valuemin="0" aria-valuemax="100"></div>
          </div>
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
.shopping-title , .electro-title, .travels-title {
  font-family: Suprema;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  color: #AEAEAE;
}
.stats-\% {
  color: #696969;
  margin-top: -20px;
  font-family: 'Dongle', sans-serif;
  font-size: 23.9789px;
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
.progress {
  height: 10px;
  width: 380px;
}
.progress-bar-shopping {
  background: linear-gradient(270deg, #FCAE73 0%, #F79042 99.18%);
  border-radius: 10.7766px;
  width: 52%;
}
.progress-bar-electro {
  background: linear-gradient(90deg, #209D43 0%, #2BC255 100%);
  border-radius: 10.7766px;
  width: 21%;
}
.progress-bar-travels {
  background: #70A6E8;
  border-radius: 10.7766px;
  width: 74%;
}
</style>
