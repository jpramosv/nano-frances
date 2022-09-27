<template>
  <section>
    <div class="container-apresentacao">
      <div class="apresentacao">
        <div class="nano">
          <h2 class="bj">Bonjour, eu sou <br /><b>Fabiana Nanô</b></h2>
          <p>
            Professora de francês, amante da França, de arte, livros e vinhos
          </p>

          <h2 class="apr">
            "Sou brasileira, moro em São Paulo e ensino francês desde 2008.<br /><br />

            Comecei a dar aulas assim que voltei da França. Lá, realizei um
            intercâmbio universitário em Lyon, uma cidade maravilhosa conhecida
            por sua gastronomia e belas paisagens.
            <br /><br />
            Voltei para o Brasil, e desde então descobri a minha grande paixão:
            ensinar esta língua que eu amo tanto.
            <br /><br />
            Ao longo desses anos, tive contato com centenas de alunos e pude
            perceber o que funciona de verdade para eles falarem francês de
            forma fluída e prazerosa.
            <br /><br />
            Reuni neste curso as principais técnicas para você dar os primeiros
            passos nesta língua charmosa e conseguir se comunicar em francês de
            forma satisfatória.
          </h2>
        </div>

        <div>
          <img
            class="fotoNano"
            src="https://fabiananano.com/wp-content/uploads/2022/03/fabiana-nano-1024x1024.webp"
          />
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "ApresentacaoView",
};
</script>

<style>
.apresentacao {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  margin: 0 auto;
  padding: 50px;
  align-items: center;
  justify-content: center;
}
.fotoNano {
  max-width: 500px;
}
.nano {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-family: "Poppins", Sans-serif;
  font-weight: 500;
  letter-spacing: 0.4px;
  max-width: 440px;
  padding: 50px;
}
.bj {
  color: #141414;
  font-family: "Poppins", Sans-serif;
  font-size: 27px;
  font-weight: 500;
  letter-spacing: 0.4px;
}
.apr {
  color: #212529cc;
  font-family: "Poppins", Sans-serif;
  font-size: 16px;
  font-weight: 400;
  line-height: 20px;
  letter-spacing: 0.6px;
}

p {
  color: #212529cc;
}
.container-apresentacao {
  background-color: #f2f2f2;
}
</style>
