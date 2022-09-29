<template>
    <section class="payment">
        <div class="payment-ctn">
            <h1>E quanto você vai investir para aprender francês em até 3 meses e realizar seu sonho de ir para a França
                falando a língua?</h1>
            <h2>Infinitamente menos do que todo o tempo e dinheiro que você vem perdendo por não ter uma rotina de
                estudos estruturada e um método claro que te faça destravar de vez na língua</h2>
            <h2>Aproveite agora e adquira o curso com todos os <strong> <u> <i>bônus de R$ 897,00 </i></u> </strong>POR
                APENAS:
            </h2>
            <h3>12x R$ 19,19</h3>
            <h4>ou à vista <span>R$ 197,00</span>
                por tempo limitado</h4>
            <div class="btn">
                <a class="about-btn" href="#"> > Sim, eu quero começar agora!</a>
                <p>*Você será direcionado para a página de pagamento</p>
            </div>

        </div>

    </section>

</template>

<script>
export default {
    name: 'PaymentSection'
}
</script>

<style>
.payment {
    background-color: #f2f2f2;

}

.payment-ctn {
    max-width: 960px;
    margin: 0 auto;
    display: flex;
    padding: 80px;
    flex-direction: column;
    text-align: center;
}

.payment-ctn h1 {
    color: #141414;
    font-family: "Poppins", Sans-serif;
    font-size: 22px;
    font-weight: 700;
}

.payment-ctn h2 {
    color: #141414;
    font-family: "Poppins", Sans-serif;
    font-size: 20px;
    font-weight: 400;
    line-height: 27px;
    padding: 30px 0 0 0;
}

.payment-ctn h3 {
    color: #478E88;
    font-family: "Poppins", Sans-serif;
    font-size: 3rem;
    font-weight: 900;
    line-height: 27px;
    margin-bottom: 0px;

}

.payment-ctn span {
    color: #478E88;


}

.payment-ctn h4 {
    color: #141414;
    font-family: "Poppins", Sans-serif;
    font-size: 28px;
    font-weight: 900;
    line-height: 35px;
}


.about-btn {
    font-family: 'Lato';
    font-style: normal;
    text-decoration: none;
    text-align: center;
    font-size: 1.8em;
    display: block;
    width: 90%;
    height: 70px;
    padding: 15px 0;
    background: #003869;
    border-radius: 5px;
    color: #E5E5E5;
}

.about-btn a {
    font-family: "Poppins", Sans-serif;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1.8px;
}

.btn {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

.payment-ctn p {
    color: #141414;
    font-family: "Poppins", Sans-serif;
    font-size: 18px;
    font-weight: 600;
    line-height: 27px;
}

@media(max-width:600px) {

    .payment-ctn h3 {
        color: #478E88;
        font-family: "Poppins", Sans-serif;
        font-size: 8vw;
        font-weight: 900;
        line-height: 27px;
        margin-bottom: 0px;

    }

    .payment-ctn h4 {
        font-size: 5vw;
    }

    .about-btn {
        font-size: 4.8vw;
    }

}
</style>