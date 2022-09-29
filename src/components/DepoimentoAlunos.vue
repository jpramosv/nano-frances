<template>
    <section class="alunos">
        <h1>O que dizem os meus alunos?</h1>
        <div class="alunos-ctn">
            <div class="depo">
                <h2>Aluna Gilda</h2>
                <div class="media">
                    <video
                        src="https://fabiananano.com/wp-content/uploads/2022/02/Aprendeu-frances-com-facilidade-1.mp4"
                        controls></video>
                </div>
            </div>
            <div class="depo">
                <h2>Aluno Leonardo</h2>
                <div class="media">
                    <img src="https://fabiananano.com/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2022/09/depoimento-leo-2.jpg.webp"
                        alt="">
                </div>
            </div>
            <div class="depo">
                <h2>Aluno Wellington</h2>
                <div class="media">
                    <img src="https://fabiananano.com/wp-content/webp-express/webp-images/doc-root/wp-content/uploads/2022/04/depoimento-wellington2.jpg.webp"
                        alt="">
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name: "DepoimentoAlunos",
};
</script>

<style>
.alunos {
    text-align: center;
    background-color: #f2f2f2;
    padding: 50px 0 50px 0;
}

.alunos-ctn {
    max-width: 960px;
    display: flex;
    margin: 0 auto;
    align-items: center;
    justify-content: center;
    text-align: center;


}

.depo {
    width: 30%;
    margin: 50px 0 0 50px;
}

.alunos h1 {
    color: #141414;
    font-family: "Poppins", Sans-serif;
    font-size: 2.3em;
    font-weight: 700;
}

.depo h2 {
    color: #141414;
    font-family: "Poppins", Sans-serif;
    font-size: 20px;
    font-weight: 700;
    padding-bottom: 20px;
}

.media img {
    max-width: 100%;
}

.media video {
    max-width: 100%;
}

@media (max-width: 768px) {
    .alunos-ctn {
        flex-direction: column;
    }

    .depo {
        width: 90%;
        margin: 0 auto;
    }
}
</style>