<template>
  <section class="home">
    <div class="home-container">
      <h1>Fale francês em três meses</h1>
      <div>
        <blockquote class="quote-externo">
          <p>Com apenas 15 minutos por dia, mesmo que você não saiba nada ou ache uma língua difícil.</p>
        </blockquote>
      </div>
    </div>

  </section>
</template>

<script>
export default {
  name: "TopoView",
};
</script>

<style>
* {
  box-sizing: border-box;
}

body,
h1,
h2,
p,
ul,
li,
a {
  margin: 0px;
  padding: 0px;
}

.home {
  width: 100%;
  height: 480px;
  background: url("@/assets/2.jpg") no-repeat center;
  background-size: cover;
  opacity: 90%;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.home-container {
  max-width: 960px;

}

.home h1 {
  font-size: 3rem;
  color: white;
  font-weight: bold;
  text-transform: uppercase;
  font-family: "Poppins", Sans-serif;
  font-weight: 700;
  letter-spacing: 1.1px;
}



.quote-externo p:before,
.quote-externo p:after {
  content: "";
  display: block;
  width: 3em;
  height: 0.3em;
  background: white;
  margin: 10px auto;
}

.home p {
  color: #ffffff;
  font-family: "Poppins", Sans-serif;
  text-align: center;
  font-size: 1.2rem;


}

@media (max-width: 1024px) {
  .home {
    text-align: center;
    width: 100%;
    height: 300px;
    background: url("@/assets/2.jpg") no-repeat center;
    background-size: cover;
  }

  .home h1 {
    color: #ffffff;
    font-family: "Poppins", Sans-serif;
    font-size: 2em;
    font-weight: 700;
    letter-spacing: 1.1px;

  }

  .home p {

    font-size: 0.9 em;

  }
}

@media (max-width: 700px) {
  .home {
    text-align: center;
    width: 100%;
    height: 300px;
    background: url("@/assets/3.jpg") no-repeat center;
    background-size: cover;
  }

  .home h1 {
    color: #ffffff;
    font-family: "Poppins", Sans-serif;
    font-size: 2em;
    font-weight: 700;
    letter-spacing: 1.1px;

  }

  .home p {

    font-size: 0.em;

  }
}
</style>