<template>
    <section class="exp">
        <div class="exp-ctn">
            <h1>7 dias</h1>
            <div class="item-exp">
                <h2>Experimente agora!</h2>
                <p>O RISCO é TODO MEU. Em até 7 DIAS depois do pagamento, você pode cancelar por qualquer motivo, e
                    devolvemos todo o valor pago.</p>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: 'ExperimenteSection'
}
</script>

<style>
.exp-ctn {
    background: #003869;
    max-width: 960px;
    height: 200px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    text-align: center;
    border-radius: 5px;
    color: #FFFFFF;
}

.exp-ctn h1 {
    width: 50%;
}

.exp-ctn h1 {
    color: #FFFFFF;
    font-family: "Roboto", Sans-serif;
    font-weight: 700;
    font-size: 3.5em;
}

.exp-ctn h2 {
    color: #FFFFFF;
    font-family: "Roboto", Sans-serif;
    font-weight: 700;
    font-size: 1.5em;
}

.item-exp p {
    color: #FFFFFF;
    font-family: "Roboto", Sans-serif;
    font-weight: 700;
    font-size: 1em;
    margin-top: 20px;
}


.item-exp {
    display: flex;
    flex-direction: column;
    text-align: left;
    padding-left: 30px;

}

item-exp p {
    width: 40%;
    color: #FFFFFF;
    font-family: "Roboto", Sans-serif;
    font-weight: 700;
    font-size: 3em;
}

@media(max-width:724px) {
    .exp-ctn {
        flex-direction: column;
    }

    .item-exp {
        text-align: center;
    }
}
</style>