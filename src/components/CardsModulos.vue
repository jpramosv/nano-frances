<template>
  <section class="modules">
    <div class="modules-container">
      <h2>Veja o que você vai aprender no curso:</h2>
      <div class="cards">
        <div class="card">
          <img src="https://fabiananano.com/wp-content/uploads/2022/02/cafe-frances.webp" alt="Avatar"
            style="width: 100%" />
          <div class="container-card">
            <h2><b>Módulos 0, 1 e 2</b></h2>
            <p>
              Aqui, você vai aprender as técnicas para estudar e realizar as tarefas do curso; também vai aprender a
              cumprimentar, se despedir, a se apresentar e a falar do seu trabalho e dos seus gostos em francês,
              treinando a pronúncia desde a primeira aula.
            </p>
          </div>
        </div>
        <div class="card">
          <img src="https://fabiananano.com/wp-content/uploads/2022/02/estudando-frances.webp" alt="Avatar"
            style="width: 100%" />
          <div class="container-card">
            <h2><b>Módulos 3, 4 e 5</b></h2>
            <p>
              Nestes módulos, estudaremos itinerários e lugares na cidade; você saberá como propor encontros em francês
              e como se expressar em lugares turísticos; também aprenderá a falar da sua rotina, obrigações e dos seus
              horários em francês.
            </p>
          </div>
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
.modules-container {
  max-width: 960px;
  margin: 50px auto;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}

.modules-container h2 {
  color: #141414;
  font-family: "Poppins", Sans-serif;
  font-size: 2.5em;
  font-weight: 700;
}

.cards {
  display: flex;
  align-items: center;
  justify-content: center;

}

.card {
  width: 60%;
  box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
  transition: 0.3s;
  margin: 20px;
  padding: 10px;
  border-radius: 10px;
}

.card h2 {
  color: #141414;
  font-family: "Poppins", Sans-serif;
  font-size: 19px;
  font-weight: 700;
  text-align: center;
}

.card p {
  text-align: justify;
  color: #212529CC;
  font-family: "Poppins", Sans-serif;
  font-size: 16px;
  font-weight: 500;
  line-height: 20px;

}

.card:hover {
  box-shadow: 0 8px 16px 0 rgba(0, 0, 0, 0.2);
}


.container-card {
  padding: 20px 16px;
}

.container-card p {
  padding-top: 20px;
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
  .cards {
    flex-wrap: wrap;
  }

  .card {
    width: 80%;
    box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
    transition: 0.3s;
    padding: 10px;
    border-radius: 10px;
  }

  .modules-container h2 {
    font-size: 5vw;
  }
}
</style>