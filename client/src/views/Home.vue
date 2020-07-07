<template>
  <div class="home">
    <div class="secondNav">
      <div>
        <h1>
        𝘽𝙞𝙠𝙞𝙣 
        </h1>
      </div>
      <hr />

      <div class="secondNavChild">
        <p>
          <router-link to="/" style="text-decoration:none; color: black; "
            >Home</router-link
          >
        </p>
        <p>
          <router-link to="/" style="text-decoration:none; color: black;"
            >Harga Website</router-link
          >
        </p>
        <p>
          <router-link to="/" style="text-decoration:none; color: black;"
            >Aplikasi Mobile</router-link
          >
        </p>
        <p>
          <router-link to="/" style="text-decoration:none; color: black;"
            >Harga Website</router-link
          >
        </p>
        <p>
          <router-link to="/" style="text-decoration:none; color: black;"
            >Hubungi Kami</router-link
          >
        </p>
      </div>
      <div class="foto">
        <div class="col-md-6">
          <img src="../assets/fotoOrangKerja.svg" />
        </div>
        <div class="card shadow">
          <div class="h4Card">
            <h2 style="font-size:">Jasa Pembuatan Website</h2>
          </div>
          <div style="padding: 10px; text-align: center; " class="my-auto">
            <h2 style="font-size: 60px; font-weight: bold; ">
              Membuat Bisnis Anda Semakin Dikenal
            </h2>
          </div>
          <button
            class="btn btn-warning btn-md"
            style="width: 400px; margin: auto; background-color: #E29216;"
          >
            <h3>
              Buatkan Saya Website
              <span><i class="fa fa-play-circle" aria-hidden="true"></i></span>
            </h3>
          </button>
        </div>
      </div>
    </div>
    <AndaButuhkan/>
    <HargaTokoOnline />
  </div>
</template>

<script>
import AndaButuhkan from "../components/AndaButuhkan"
import HargaTokoOnline from "../components/HargaTokoOnline"
export default {
  name: "Home",
  components: {
    AndaButuhkan,
    HargaTokoOnline 
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
</style>
