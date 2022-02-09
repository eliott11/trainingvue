<template>
  <section class="newtran block-shadow">
    <h4>New Transaction</h4>
      <div class="newtrans-section">
        <div class="transcontent-left">
          <div class="content-top">
            <div>
              <div>Photo</div>
              <div>Name</div>
            </div>
            <div>
                <div>Photo</div>
                <div>Name</div>
            </div>
            <div>
                <div>Photo</div>
                <div>Name</div>
            </div>
          </div>
          <div class="btn-bottom">
              <input type="$">
              <button>Send Transfert ></button>
          </div>
        </div>
        
        <div class="transcontent-right">
            <div>Get great loan! ></div>
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
.newtrans-section {
  display: flex;
}
</style>
