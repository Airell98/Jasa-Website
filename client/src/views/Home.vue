<template>

  <main class="home">

    <section class="introduction-container">
      <img class="introduction-image" src="../assets/done_website_undraw.svg" />
      <div class="introduction-sentences">
        <h1 class="introduction-sentences-title" >Solusi bisnis masa kini</h1>
        <p class="introduction-sentences-paragraph" >Kami memberikan kemudahan dalam memperkenalkan bisnis anda ke dunia digital.</p>
      </div>
    </section>

    <AndaButuhkan/>

    <HargaTokoOnline />
    
  </main>
</template>

<script>
import AndaButuhkan from "../components/AndaButuhkan"
import HargaTokoOnline from "../components/HargaTokoOnline"
export default {
  name: "Home",
  components: {
    AndaButuhkan,
    HargaTokoOnline,
    Header
  },
};
</script>

<style scoped>
.secondNav {
  background-color: rgb(252, 252, 252);
}
.secondNavChild {
  display: flex;
  justify-content: space-evenly;
  margin: 16px;
  font-size: 20px;
  font-weight: 560;
}

.foto {
  display: flex;
  padding: 20px;
  justify-content: space-evenly;
  color: black;
}

.card {
  max-width: 500px;
}
.h4Card {
  background-color: #E29216;
}

.introduction-container {
  display: flex;
  margin-bottom: 50px;
}

.introduction-image {
  flex: 3;
  margin: 10px;
}
.introduction-sentences {
  flex: 2;
  display: flex;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  margin: 10px;
}

.introduction-sentences-title {
  color: #79a8a9;
  font-weight: bold;
  margin-bottom: 30px;
}

.introduction-sentences-paragraph {
  color: #1f4e5f;
  font-size: 2em;
  margin-bottom: 30px;
}
</style>
