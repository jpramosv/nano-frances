<template>
    <section>
        <div class="header-ctn">
            <div class="header-img">
                <div class="header-item">
                    <img src="https://fabiananano.com/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2021/09/logo-vertical-colorido-sem-fundo-2048x2048.png.webp"
                        alt="">
                </div>
                <div class="header-item copy">
                    <h1>Copyright 2021 © Todos os direitos reservados para Fabiana Nanô.</h1>
                    <h1>CNPJ: 24.922.623/0001-80</h1>
                    <h1>E-mail de contato: fabiana@fabiananano.com</h1>
                </div>
            </div>
            <h1>Esse produto é comercializado com apoio da Hotmart. A plataforma não faz controle editorial prévio dos
                produtos comercializados, nem avalia a tecnicidade e experiência daqueles que os produzem. A existência
                de um produto e sua aquisição, por meio da plataforma, não podem ser consideradas como garantia de
                qualidade de conteúdo e resultado, em qualquer hipótese. Ao adquiri-lo, o comprador declara estar ciente
                dessas informações. Os termos e políticas da Hotmart podem ser acessados aqui, antes mesmo da conclusão
                da compra.</h1>

        </div>
    </section>
</template>

<script>
export default {
    name: 'HeaderNano'
}
</script>

<style>
.header-ctn {
    max-width: 960px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
}

.header-img {
    display: flex;
    align-items: center;
}

.header-item {
    width: 50%;

}

.header-img img {
    width: 50%;
}

.header-img h1 {
    color: #000032;
    font-family: "Poppins", Sans-serif;
    font-size: 15px;
    font-weight: 500;
    line-height: 18px;
    padding: 10px;
}

.header-item:nth-child(1) {
    display: flex;
    align-items: center;
    justify-content: center;
}

.header-ctn>h1 {
    color: #003869;
    font-family: "Poppins", Sans-serif;
    font-size: 14px;
    font-weight: 300;
    -webkit-text-stroke-color: #000;
    stroke: #000;
    text-align: center;
}

@media(max-width:624px) {
    .header-ctn {
        flex-direction: column;
    }

    .header-img {
        flex-direction: column;
    }

    .header-ctn>h1 {
        font-size: 0.8;
        padding: 10px;
    }

    .header-img h1 {
        padding: 4px;
        font-size: 12px;

    }

    .header-item {
        width: 100%;
        text-align: center;


    }
}
</style>