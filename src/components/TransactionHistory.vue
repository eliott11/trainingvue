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
                    <td class="name-trans"><i class="bi bi-cart"></i>Tesco Market</td>
                    <td class="type-name">Shopping</td>
                    <td class="date">13 Dec 2020</td>
                    <td class="amount">75.67$</td>
                </tr>
                <tr>
                    <td class="name-trans"><i class="bi bi-truck"></i>ElectroMen Market</td>
                    <td class="type-name">Shopping</td>
                    <td class="date">14 Dec 2020</td>
                    <td class="amount">250.00$</td>
                </tr>
                <tr>
                    <td class="name-trans"><i class="bi bi-arrow-down-left"></i>Fiorgo Restaurant</td>
                    <td class="type-name">Food</td>
                    <td class="date">7 Dec 2020</td>
                    <td class="amount">19.50$</td>
                </tr>
                <tr>
                    <td class="name-trans"><i class="bi bi-person"></i>John Matthew Kayne</td>
                    <td class="type-name">Sport</td>
                    <td class="date">6 Dec 2020</td>
                    <td class="amount">350$</td>
                </tr>
                <tr>
                    <td class="name-trans"><i class="bi bi-person"></i>Ann Marlin</td>
                    <td class="type-name">Shopping</td>
                    <td class="date">31 Nov 2020</td>
                    <td class="amount">430$</td>
                </tr>
            </tbody>
        </table>
    </div>
  </section>
</template>

<script>
export default {
  name: 'TransactionHistory',
  props: {}
}
</script>

<style scoped>
th {
    text-align: start;
    font-weight: lighter;
    margin: 10px;
}
i {
    margin-right: 10px;
    background-color: #EFEFEF;
    border-radius: 5px;
    padding: 3px;
}
td[class*="name-trans"] {
    display: flex;
}
.bi-cart, .bi-truck, .bi-arrow-down-left, .bi-person, .bi-person {
  display: flex;
  align-items: center;
}
.amout, .name-trans {
    color: black;
}
th {
    color: #AEAEAE;
}
.type-name, .date {
    color: #C7C7C7;
}
.amount {
    text-align: end;
}
</style>
