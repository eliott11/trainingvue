<template>
  <section class="cards block-shadow">
    <h4>Cards</h4>
    <div class="content-card">

      <div class="top-info"> <!--- Infos top --->

        <div class="card-user"> <!--- Infos card left --->
          <div class="card-account">
            <div>cloudcash</div>
            <div>PREMIUM ACCOUNT</div>
          </div>
          <div class="card-number">
            5789 **** **** 2847
          </div>
          <div class="bot-card">
            <div class="holder">
              <div>Card Holder</div>
              <div>Mike Smith</div>
            </div>
            <div class="expire">
              <div>Expire date</div>
              <div>06/21</div>
            </div>
          </div>
        </div>
        
        <div class="bot-info"> <!--- Infos bottom --->
          <div>
            <div class="bar-progress">
              <div class="progress  mb-1"> <!--- progress bar --->
                <div class="progress-bar-card" role="progressbar" aria-valuenow="74" aria-valuemin="0" aria-valuemax="100"></div>
              </div>
            </div>
            <div class="stats-bar">
              <span>Weekly payment limit</span>
              <span>$350.60 / $4000</span>
            </div>
          </div>
        </div>

      </div>
      
      <div class="card-stats"> <!--- Stats card right --->
          <div class="stats-bloc">
            <div class="balance">$ 2850.75</div>
            <div class="subtitle-stats">Current Balance</div>
          </div>
          <div class="stats-bloc">
            <div class="income">$ 1500.50</div>
            <div class="subtitle-stats">Income</div>
          </div>
          <div class="stats-bloc">
            <div class="outcome">$ 350.60</div>
            <div class="subtitle-stats">Outcome</div>
          </div>
          <div class="btn-desactivate">
            <!-- <i class="bi bi-toggle-off"></i> -->
            <div class="btn-ext">
              <div class="btn-int"></div>
            </div>
            <span>Deactivate Card</span>
          </div>
      </div>

    </div>
  </section>
</template>

<script>
export default {
  name: 'Cards',
  props: {
    
  }
}
</script>

<style scoped>
.content-card {
  margin-bottom: 15px;
  display: flex;
  height: 85%;
  justify-content: space-between;
}
.top-info {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}
.card-user {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: 65%;
  background: linear-gradient(180deg, #197BBD 0%, #3391D0 100%);
  border-radius: 26px;
  color: #ffffff;
}


.card-account, .card-number, .bot-card {
  margin-left: 15px;
}
/* Stats card right */
.balance {
  color: #197BBD;
}
.income {
  color: #439A86;
}
.outcome {
  color: #BB4430;
}
.balance, .income, .outcome {
  font-size: 18px;
  line-height: 22px;
}
.balance {
  font-weight: bold;
}
.subtitle-stats {
  color: #AEAEAE;
  font-size: 14px;
  line-height: 17px;
}
.card-stats {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-end;
}

.card-stats, .btn-desactivate {
  text-align: end;
}
.btn-desactivate {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.btn-ext {
  background: #EBEBEB;
  border-radius: 13.617px;
  width: 45.69px;
  height: 23.45px;
}
.btn-int {
  background: #CDCDCD;
  border-radius: 13.617px;
  width: 23.45px;
  height: 23.45px;
}
.btn-int, .btn-ext {
  align-self: flex-end;
} /*
.bot-info {
  display: grid;
  grid-template-columns: 65% 35%;
}
.stats-bar {
  display: flex;
  justify-content: space-between;
}
.bot-card {
  display: flex;
}
progressbar
.progress { progress bar general
  height: 9.47px;
  width: 380px;
}
.progress-bar-card { progress bar travels filling
  background: #70A6E8;
  border-radius: 10.7766px;
  width: 74%;
} */
</style>
