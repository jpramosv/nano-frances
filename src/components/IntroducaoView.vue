<template>
  <section class="container-introducao">
    <div class="introducao">
      <h2>Querido amante da língua francesa,</h2>

      <p>Se você planeja uma viagem à França, quer realizar um intercâmbio lá, ter mais oportunidades de trabalho aqui
        no Brasil ou até mesmo na França...
      </p>
      <p>
        Se você quer falar francês ainda em 2022, mas não tem ideia de por onde começar...
      </p>
      <p>
        Se você está cansado de procrastinar seus estudos por falta de rotina ou de uma mentora que te guie...
      </p>

      <p>
        Se você quer aprender a se expressar em francês com a pronúncia correta e seguindo um método claro, leve,
        dinâmico e prático...
      </p>

      <i>Então você chegou ao lugar certo!</i>

      <p>
        No curso <b>Francês em 3 Meses</b> eu vou te ensinar o método mão na
        massa para você aprender a se comunicar em francês com uma boa
        pronúncia, mesmo que você nunca tenha estudado ou ache uma língua
        difícil.
      </p>

    </div>
  </section>
</template>

<script>
export default {
  name: "IntroducaoView",
};
</script>

<style>
.container-introducao {
  background-color: #f7f8f9;
  display: flex;
  align-items: center;
  justify-content: center;
}

.introducao {
  max-width: 960px;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 50px;
  text-align: center;
}

.introducao h2 {
  color: #141414;
  font-family: "Poppins", Sans-serif;
  font-size: 27px;
  font-weight: 800;
  letter-spacing: 0.4px;
}

.introducao p {
  color: #212529CC;
  font-family: "Lato", Sans-serif;
  font-size: 19px;
  font-weight: 400;
  line-height: 28px;
  letter-spacing: 0.6px;
  padding: 20px;
}

.introducao i {
  color: #212529CC;
  font-family: "Lato", Sans-serif;
  font-size: 19px;
  font-weight: 400;
  line-height: 28px;
  letter-spacing: 0.6px;
}
</style>