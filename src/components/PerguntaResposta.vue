<template>
    <section class="pergunta">
        <div class="perguntar-ctn">
            <h1>Perguntas e respostas</h1>
            <h2>Seguem abaixo algumas dúvidas recorrentes que você pode vir a ter, assim você pode tirar todas as
                dúvidas
                necessárias e seguir tranquilo(a) na sua decisão.</h2>
            <div class="resposta">
                <div class="linha">
                    <div class="resposta-item">
                        <h1>Q. Onde receberei os dados para acessar o curso?</h1>
                        <p>
                            <strong>A.</strong> Após o pagamento, você receberá automaticamente em seu e-mail
                            cadastrado os seus dados de
                            acesso. É importante que você guarde este e-mail e, como sugestão, pode "favoritar" em seu
                            navegador a página de acesso ao curso. Caso não encontre este e-mail, procure em sua caixa
                            de spam e, ainda não encontrando, entre em contato com a equipe de suporte através do e-mail
                            suporte@fabiananano.com
                        </p>
                    </div>
                    <div class="resposta-item">
                        <h1>Q. Onde receberei os dados para acessar o curso?</h1>
                        <p> <strong>A.</strong> Após o pagamento, você receberá automaticamente em seu e-mail cadastrado
                            os seus dados de
                            acesso. É importante que você guarde este e-mail e, como sugestão, pode "favoritar" em seu
                            navegador a página de acesso ao curso. Caso não encontre este e-mail, procure em sua caixa
                            de spam e, ainda não encontrando, entre em contato com a equipe de suporte através do e-mail
                            suporte@fabiananano.com</p>
                    </div>
                </div>
                <div>
                    <div class="resposta-item">
                        <h1>Q. Onde receberei os dados para acessar o curso?</h1>
                        <p> <strong>A.</strong> Após o pagamento, você receberá automaticamente em seu e-mail cadastrado
                            os seus dados de
                            acesso. É importante que você guarde este e-mail e, como sugestão, pode "favoritar" em seu
                            navegador a página de acesso ao curso. Caso não encontre este e-mail, procure em sua caixa
                            de spam e, ainda não encontrando, entre em contato com a equipe de suporte através do e-mail
                            suporte@fabiananano.com</p>
                    </div>
                    <div class="resposta-item">
                        <h1>Q. Onde receberei os dados para acessar o curso?</h1>
                        <p> <strong>A.</strong> Após o pagamento, você receberá automaticamente em seu e-mail cadastrado
                            os seus dados de
                            acesso. É importante que você guarde este e-mail e, como sugestão, pode "favoritar" em seu
                            navegador a página de acesso ao curso. Caso não encontre este e-mail, procure em sua caixa
                            de spam e, ainda não encontrando, entre em contato com a equipe de suporte através do e-mail
                            suporte@fabiananano.com</p>
                    </div>
                </div>
            </div>
            <a class="about-btn" href="#"> > Sim, eu quero começar agora!</a>
        </div>
    </section>
</template>

<script>
export default {
    name: 'PerguntaResposta'
}
</script>

<style>
.pergunta {
    background-color: #f2f2f2;
}

.perguntar-ctn {
    max-width: 960px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
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
    margin-top: 2em;
}

.about-btn a {
    font-family: "Poppins", Sans-serif;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 1.8px;
}

.resposta {
    display: flex;
}

.perguntar-ctn>h1 {
    color: #000032;
    font-family: "Poppins", Sans-serif;
    font-size: 43px;
    font-weight: 700;
    padding-top: 2em;
}

.perguntar-ctn>h2 {
    color: #000032;
    font-family: "Poppins", Sans-serif;
    font-size: 16px;
    font-weight: 700;
    line-height: 23px;
    text-align: center;
    padding-bottom: 3em;
    padding-top: 0.5em;
}

.resposta h1 {
    color: #000032;
    font-family: "Poppins", Sans-serif;
    font-size: 13px;
    font-weight: 700;
    line-height: 23px;
}

.resposta p {
    color: #000032;
    font-family: "Poppins", Sans-serif;
    font-size: 13px;
    font-weight: 400;
    line-height: 23px;
}

.linha {
    border-right: 1px solid #16085b;
}

.resposta-item {
    margin: 40px;
}

.resposta-item p {
    padding-top: 5px;

}

@media(max-width:624px) {
    .resposta {
        flex-direction: column;
    }

    .linha {
        border-right: 0px solid #16085b;
    }

    .about-btn {
        font-size: 1.5em;
    }

    .perguntar-ctn>h1 {
        text-align: center;
    }
}
</style>