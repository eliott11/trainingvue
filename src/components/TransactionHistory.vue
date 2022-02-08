<template>
    <section class="transactionhistory block-shadow">
        <h4>Transaction History</h4>
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
                    <td><div class="name-trans"><i class="bi bi-cart"></i>Tesco Market</div></td>
                    <td class="type-name">Shopping</td>
                    <td class="date">13 Dec 2020</td>
                    <td class="amount">75.67$</td>
                </tr>
                <tr>
                    <td><div class="name-trans"><i class="bi bi-truck"></i>ElectroMen Market</div></td>
                    <td class="type-name">Shopping</td>
                    <td class="date">14 Dec 2020</td>
                    <td class="amount">250.00$</td>
                </tr>
                <tr>
                    <td><div class="name-trans"><i class="fas fa-feather"></i>Fiorgo Restaurant</div></td>
                    <td class="type-name">Food</td>
                    <td class="date">7 Dec 2020</td>
                    <td class="amount">19.50$</td>
                </tr>
                <tr>
                    <td><div class="name-trans"><i class="bi bi-person"></i>John Matthew Kayne</div></td>
                    <td class="type-name">Sport</td>
                    <td class="date">6 Dec 2020</td>
                    <td class="amount">350$</td>
                </tr>
                <tr>
                    <td><div class="name-trans"><i class="bi bi-person"></i>Ann Marlin</div></td>
                    <td class="type-name">Shopping</td>
                    <td class="date">31 Nov 2020</td>
                    <td class="amount">430$</td>
                </tr>
            </tbody>
        </table>
    </section>
</template>

<script>
export default {
  name: 'TransactionHistory',
  props: {}
}
</script>

<style scoped>
table {
    width:-webkit-fill-available;
    height: 215px;
}
th {
    text-align: start;
    font-weight: lighter;
    margin: 10px;
    color: #AEAEAE;
}
tbody {
    font-style: normal;
    font-weight: normal;
    font-size: 14px;
    line-height: 17px;
}
td {
    border-bottom: 0.5px solid #ECECEC; /* à appliquer sur le TR pr faire une ligne entière mais veut pas (à résoudre)*/
}
td[class*="name-trans"] {
    display: flex;
    align-items: center;
}
i {
    margin-right: 10px;
    background-color: #EFEFEF;
    border-radius: 5px;
    padding: 3px;
}
.name-trans {
    display: flex;
    flex-direction: row;
    align-items: center;
}
.bi-cart, .bi-truck, .fa-feather, .bi-person, .bi-person {
  display: flex;
  align-items: center;
}
.name-trans, .amount {
    color: #404040;
}
.type-name, .date {
    color: #C7C7C7;
    margin: 5px 10px;
}
.amount {
    text-align: end;
    font-weight: bold;
}
</style>
