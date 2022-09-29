<template>
    <section class="bonus">
        <h1>E tem mais! Ainda vou te dar <span>6 bônus </span> especiais:</h1>
        <div class="bonus-container">
            <ul class="bonus-list">
                <li><b>Bônus 1:</b> Como treinar a sua escuta do francês </li>
                <li><b>Bônus 2:</b> Grupo exclusivo de alunos no Telegram para dúvidas de pronúncia</li>
                <li><b>Bônus 3:</b> Como soletrar seu nome e e-mail em francês</li>
                <li><b>Bônus 4:</b> Como dizer seu número de telefone</li>
                <li><b>Bônus 5:</b> Como se localizar pelos arrondissements (distritos) em Paris, Lyon e Marseille</li>
                <li><b>Bônus 6:</b> Como formular perguntas em francês</li>
            </ul>
        </div>
    </section>
</template>

<script>
export default {
    name: 'BonusCourse'
}
</script>

<style>
.bonus h1 {
    text-align: center;
    padding: 40px;
    color: #141414;
    font-family: "Poppins", Sans-serif;
    font-size: 33px;
    font-weight: 700;
}

.bonus-container {
    max-width: 960px;
    margin: 0 auto;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    border-radius: 10px;

}

.bonus-list {
    padding: 20px;
}

.bonus-list li {
    list-style: none;
    padding: 10px 40px 20px 40px;
    margin-left: 15px;
    background-image: url("@/assets/accept.svg");
    background-repeat: no-repeat;
    background-position: left center;
    background-size: 30px;
    font-family: "Poppins", Sans-serif;
    font-weight: 400;
}

ul {
    columns: 2;
}

.bonus span {
    color: rgb(110, 193, 228);
}
</style>