<template>
  <section class="Catalog">

    <h1 class="Catalog-Title">Apa Yang Anda Butuhkan</h1>

    <div class="Catalog-List-Container">

      <div class="Catalog-List">
        <img class="Catalog-List-Icon" src="../assets/Shopping_Cart.svg" />
        <h3 class="Catalog-List-Title">Website Toko Online</h3>
        <p class="Catalog-List-Desc">Saya ingin memiliki website untuk memasarkan produk-produk saya.</p>
      </div>

      <div class="Catalog-List">
        <img class="Catalog-List-Icon" src="../assets/company.svg" />
        <h3 class="Catalog-List-Title">Website Perusahaan</h3>
        <p class="Catalog-List-Desc">Saya ingin membuat website profil untuk perusahaan saya yang bergerak dibidang jasa atau agensi.</p>
      </div>

      <div class="Catalog-List">
        <img class="Catalog-List-Icon" src="../assets/iphone.svg" />
        <h3 class="Catalog-List-Title">Aplikasi Mobile</h3>
        <p class="Catalog-List-Desc">Saya ingin membuat aplikasi Android dan iOS agar bisnis saya bisa diakses kustomer kapanpun dan dimanapun.</p>
      </div>

    </div>
    <!-- <h1 style="font-size: 50px; font-weight: 550; height: 150px ;">
      Apa Yang Anda Butuhkan?
    </h1>
    <div class="container">
      <div class="group">
        <div>
          <i class="fa fa-shopping-cart fa-4x" aria-hidden="true"></i>
        </div>
        <div class="h3">
          <h3>Website Toko Online</h3>
        </div>
        <div class="paragraph">
            <p>Saya ingin membuat website profil untuk perusahaan saya yang bergerak dibidang jasa atau agensi. </p>
        </div>
      </div>

        <div class="group">
        <div>
          <i class="fa fa-building fa-4x" aria-hidden="true"></i>
        </div>
        <div class="h3">
          <h3>Website Perusahaan</h3>
        </div>
        <div class="paragraph">
            <p>Saya ingin punya website yang ada fitur katalog produk, keranjang belanja, ongkir, diskon, dll </p>
        </div>
      </div>

      <div class="group">
        <div>
          <i class="fa fa-android fa-4x" aria-hidden="true"></i>
        </div>
        <div class="h3">
          <h3>Mobile App</h3>
        </div>
        <div class="paragraph">
            <p>Saya ingin membuat aplikasi Android dan iOS agar bisnis saya bisa diakses kustomer kapanpun dan dimanapun.</p>
        </div>
      </div>
    </div> -->
  </section>
</template>

//
<script>
export default {};
</script>

<style scoped>
.container {
  display: flex;
  justify-content: space-between;
}
.h3 {
  margin: 20px;
}

.paragraph{
    max-width: 300px;
}

.Catalog {
  background-color: #79a8a9;
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
  height: 50vh;
  margin-bottom: 10vh;
}

.Catalog-List-Container {
  max-width: 100%;
  max-height: 100%;
  position: relative;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  margin: 0 4%;
}

.Catalog-Title {
  color: #f4f7f7;
}

.Catalog-List {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-evenly;
  align-items: center;
  margin: 1%;
}

.Catalog-List-Icon {
  max-width: 35%;
  max-height: 35%;
}

.Catalog-List-Title {
  color: #f4f7f7;
  font-weight: bold;
  text-align: center;
}
.Catalog-List-Desc {
  text-align: center;
  color: #f4f7f7;
}
</style>
