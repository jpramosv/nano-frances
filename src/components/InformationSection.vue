<template>
    <section class="information">
        <div class="information-ctn">
            <div class="item-information">
                <div><img src="@/assets/computador-portatil.png" alt=""></div>
                <h1>Curso 100% Online</h1>
                <h2>Acesso imediato</h2>
            </div>
            <div class="item-information">
                <div><img src="@/assets/verificado.png" alt=""></div>
                <h1>Um ano de acesso</h1>
                <h2>Comece hoje mesmo</h2>
            </div>
            <div class="item-information">
                <div><img src="@/assets/balao-de-fala.png" alt=""></div>
                <h1>Suporte ao aluno</h1>
                <h2>Plataforma exclusiva para dúvidas</h2>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "InformationSection"
}
</script>

<style>
.information {
    background: #003869;
}

.information-ctn {
    max-width: 960px;
    height: 250px;
    margin: 50px auto;
    display: flex;
    align-items: center;
    justify-content: center;
}

.item-information {
    width: 30%;
    display: flex;
    flex-direction: column;
    align-items: center;


}

.item-information img {
    width: 30%;

}

.item-information>div {
    display: flex;
    align-items: center;
    justify-content: center;
}

.item-information h1 {
    font-family: "Poppins", Sans-serif;
    font-size: 22px;
    font-weight: 600;
    color: #FFFFFF;
    padding: 10px 0 5px 0;
}

.item-information h2 {
    font-family: "Poppins", Sans-serif;
    font-size: 16px;
    font-weight: 600;
    color: #FFFFFF;
    height: 40px;
}

@media(max-width:768px) {
    .information-ctn {
        flex-direction: column;
        height: auto;
    }

    .item-information {
        width: 210px;
    }

}
</style>