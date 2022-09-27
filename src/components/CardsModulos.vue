<template>
  <section class="sct-ctn">
    <h2>Veja o que você vai aprender no curso:</h2>
    <div class="container">
      <div class="card">
        <img
          src="https://fabiananano.com/wp-content/uploads/2022/02/digitando-na-franca.webp"
          alt="Avatar"
          style="width: 100%"
        />
        <div class="container-card">
          <h4><b>Módulo 0</b></h4>
          <p>
            Neste módulo, você vai aprender as técnicas e ferramentas para poder
            aproveitar os conteúdos e realizar as tarefas dos módulos seguintes.
          </p>
        </div>
      </div>
      <div class="card">
        <img
          src="https://fabiananano.com/wp-content/uploads/2022/02/digitando-na-franca.webp"
          alt="Avatar"
          style="width: 100%"
        />
        <div class="container-card">
          <h4><b>Módulo 0</b></h4>
          <p>
            Neste módulo, você vai aprender as técnicas e ferramentas para poder
            aproveitar os conteúdos e realizar as tarefas dos módulos seguintes.
          </p>
        </div>
      </div>
      <div class="card">
        <img
          src="https://fabiananano.com/wp-content/uploads/2022/02/digitando-na-franca.webp"
          alt="Avatar"
          style="width: 100%"
        />
        <div class="container">
          <h4><b>Módulo 0</b></h4>
          <p>
            Neste módulo, você vai aprender as técnicas e ferramentas para poder
            aproveitar os conteúdos e realizar as tarefas dos módulos seguintes.
          </p>
        </div>
      </div>
      <div class="card">
        <img
          src="https://fabiananano.com/wp-content/uploads/2022/02/digitando-na-franca.webp"
          alt="Avatar"
          style="width: 100%"
        />
        <div class="container-card">
          <h4><b>Módulo 0</b></h4>
          <p>
            Neste módulo, você vai aprender as técnicas e ferramentas para poder
            aproveitar os conteúdos e realizar as tarefas dos módulos seguintes.
          </p>
        </div>
      </div>
      <div class="card">
        <img
          src="https://fabiananano.com/wp-content/uploads/2022/02/digitando-na-franca.webp"
          alt="Avatar"
          style="width: 100%"
        />
        <div class="container-card">
          <h4><b>Módulo 0</b></h4>
          <p>
            Neste módulo, você vai aprender as técnicas e ferramentas para poder
            aproveitar os conteúdos e realizar as tarefas dos módulos seguintes.
          </p>
        </div>
      </div>
      <div class="card">
        <img
          src="https://fabiananano.com/wp-content/uploads/2022/02/digitando-na-franca.webp"
          alt="Avatar"
          style="width: 100%"
        />
        <div class="container-card">
          <h4><b>Módulo 0</b></h4>
          <p>
            Neste módulo, você vai aprender as técnicas e ferramentas para poder
            aproveitar os conteúdos e realizar as tarefas dos módulos seguintes.
          </p>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "CardsModulos",
};
</script>

<style>
.container {
  max-width: 960px;
  display: flex;
  flex-wrap: wrap;
  margin: 0 auto;
  padding: 10px;
}
.card {
  /* Add shadows to create the "card" effect */
  width: 30%;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
  padding: 10px;
  border-radius: 10px;
}

/* On mouse-over, add a deeper shadow */
.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
}

/* Add some padding inside the card container */
.container-card {
  padding: 2px 16px;
}
.title {
  margin: 0 auto;
  color: #141414;
  font-family: "Poppins", Sans-serif;
  font-size: 2vw;
}
.sct-ctn {
  display: flex;
  flex-direction: column;
  align-items: center;
}
@media (max-width: 768px) {
  .container {
    max-width: 960px;
    display: flex;
    margin: 0 auto;
    padding: 10px;
    flex-wrap: wrap;
  }
  .card {
    /* Add shadows to create the "card" effect */
    width: 80%;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    transition: 0.3s;
    padding: 10px;
    border-radius: 10px;
  }
}
</style>