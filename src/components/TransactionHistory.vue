<template>
  <section class="transactionhistory">
    <h4>Transaction History</h4>
    <div>
            <table>
                <thead>
                    <tr>
                        <th>Reciever</th>
                        <th>Type</th>
                        <th>Date</th>
                        <th>Amount</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Tesco Market</td>
                        <td>Shopping</td>
                        <td>10/5/2020</td>
                        <td>75$</td>
                    </tr>
                    <tr>
                        <td>Resto</td>
                        <td>Food</td>
                        <td>11/06/2020</td>
                        <td>50$</td>
                    </tr>
                    <tr>
                        <td>Gym</td>
                        <td>Sport</td>
                        <td>12/07/2020</td>
                        <td>30$</td>
                    </tr>
                    <tr>
                        <td>Stuff</td>
                        <td>Other</td>
                        <td>13/08/2020</td>
                        <td>100$</td>
                    </tr>
                </tbody>
            </table>
        </div>
  </section>
</template>

<script>
export default {
  name: 'TransactionHistory',
  props: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
