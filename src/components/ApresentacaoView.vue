<template>
  <section>
    <div class="container-apresentacao">
      <div class="apresentacao">
        <div class="nano">
          <h2 class="bj">Bonjour, eu sou <br /><b>Fabiana Nanô</b></h2>
          <p>
            Professora de francês, amante da França, de arte, livros e vinhos e uma boa gastronomia
          </p>
          <span class="quote"></span>
          <p>
            "Sou brasileira, moro em São Paulo e ensino francês desde 2008.
          </p>
          <p>
            Comecei a dar aulas assim que voltei da França. Lá, realizei um
            intercâmbio universitário em Lyon, uma cidade maravilhosa conhecida
            por sua gastronomia e belas paisagens.
          </p>
          <p>
            Voltei para o Brasil, e desde então descobri a minha grande paixão:
            ensinar esta língua que eu amo tanto.
          </p>
          <p>
            Ao longo desses anos, tive contato com centenas de alunos e pude
            perceber o que funciona de verdade para eles falarem francês de
            forma fluída e prazerosa.
          </p>
          <p>
            Reuni neste curso as principais técnicas para você dar os primeiros
            passos nesta língua charmosa e conseguir se comunicar em francês de
            forma satisfatória.
          </p>
        </div>

        <div class="fotoNano">
          <img src="https://fabiananano.com/wp-content/uploads/2022/03/fabiana-nano-1024x1024.webp" />
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
  flex-wrap: wrap;
  padding: 50px;
  align-items: flex-start;
  justify-content: center;
  text-align: center;
}

.fotoNano {
  max-width: 495px;
}

.fotoNano img {
  max-width: 100%;
  margin-left: 30px;
}

.nano {
  display: flex;
  flex-direction: column;
  font-family: "Poppins", Sans-serif;
  font-weight: 500;
  letter-spacing: 0.4px;
  max-width: 550px;
}

.nano p {
  padding: 18px;
}

.bj {
  color: #141414;
  font-family: "Poppins", Sans-serif;
  font-size: 27px;
  font-weight: 500;
  letter-spacing: 0.4px;
}

.quote:after {
  content: "";
  display: block;
  width: 20rem;
  height: 1px;
  background: black;
  margin: 10px auto;
}


p {
  color: #212529cc;
}

.container-apresentacao {
  background-color: #f2f2f2;
}
</style>
