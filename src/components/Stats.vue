<template>
  <section class="stats">
    <h4>Outcome Statistics</h4>

    <div class="stats-all"> <!--- class generale --->

      <div class="stats-shopping"> <!--- class card --->
        <div><i class="bi bi-cart"></i></div>
        <div class="mt-1 mb-1 bloc-bar"> <!--- margin card content --->
          <div class="bar-progress">
            <div class="progress mb-1"> <!--- progress bar --->
              <div class="progress-bar-shopping" role="progressbar" aria-valuenow="52" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
            <div class="stats-pourcentage">52%</div> <!--- % progress --->
          </div>
          <div class="shopping-title">Shopping</div>
        </div>
      </div>

      <div class="stats-electro"> <!--- class card --->
        <div><i class="bi bi-truck"></i></div>
        <div class="mt-1 mb-1"> <!--- margin card content --->
          <div class="bar-progress">
            <div class="progress mb-1"> <!--- progress bar --->
              <div class="progress-bar-electro" role="progressbar" aria-valuenow="21" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
            <div class="stats-pourcentage">21%</div> <!--- % progress --->
          </div>
          <div class="electro-title">Electronics</div>
        </div>
      </div>

      <div class="stats-travels"> <!--- class card --->
        <div><i class="fas fa-plane"></i></div>
        <div class="mt-1 mb-1"> <!--- margin card content --->
          <div class="bar-progress">
            <div class="progress  mb-1"> <!--- progress bar --->
              <div class="progress-bar-travels" role="progressbar" aria-valuenow="74" aria-valuemin="0" aria-valuemax="100"></div>
            </div>
            <div class="stats-pourcentage">74%</div> <!--- % progress --->
          </div>
          <div class="travels-title">Travels</div>
        </div>
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
.stats-shopping, .stats-electro, .stats-travels { /* cards display */
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  height: 50px;
}
.shopping-title , .electro-title, .travels-title { /* title description */
  font-family: Suprema;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  color: #AEAEAE;
}
.stats-pourcentage { /* % */
  color: #696969;
  font-family: 'Dongle', sans-serif;
  font-size: 26.98px;
  margin-left: 10px;
  line-height: 10px; /* space line */
}
.bi-cart, .bi-truck, .fa-plane { /* property icons */
  box-shadow: 0px 16px 24px rgba(0, 0, 0, 0.06), 0px 2px 6px rgba(0, 0, 0, 0.04), 0px 0px 1px rgba(0, 0, 0, 0.04);
  border-radius: 3px;
  padding: 8px;
}
.bi-cart { /* props icon & background */
  background: #FFEADA;
  color: #F8964C;
}
.bi-truck { /* props icon & background */
  background: #DDF9E4;
  color: #22A447;
}
.fa-plane { /* props icon & background */
  background: #E4F0FF;
  color: #70A6E8;
}
.progress { /* progress bar general */
  height: 9.47px;
  width: 380px;
}
.progress-bar-shopping { /* progress bar shopping filling */
  background: linear-gradient(270deg, #FCAE73 0%, #F79042 99.18%);
  border-radius: 10.7766px;
  width: 52%;
}
.progress-bar-electro { /* progress bar electro filling */
  background: linear-gradient(90deg, #209D43 0%, #2BC255 100%);
  border-radius: 10.7766px;
  width: 21%;
}
.progress-bar-travels { /* progress bar travels filling */
  background: #70A6E8;
  border-radius: 10.7766px;
  width: 74%;
}
.bar-progress { /* bar center */
  display: flex;
  align-items: center;
}
</style>
