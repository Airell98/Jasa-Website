<template>
  <div class="jumbotron">
    <h1 style="font-size: 50px; font-weight: 550; height: 150px ;">
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
    </div>
  </div>
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
</style>
