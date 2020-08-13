<template>
  <div class="success">
    <div class="d-flex justify-content-center" style="margin-top: 25vh;">
      <div class="col col-lg-3 text-center">
        <img src="img/success@2x.png" style="width: 250px;" />
      </div>
      <div class="col col-lg-4 text-left">
        <h3 class="mt-4">Pembelian Success!</h3>
        <p
          class="mt-2"
        >Terimakasih sudah berbelanja di Holic.Bag kami, untuk mengecek detail pesanan kamu kami akan kirim via gmail setelah pembayaran dilakukan.</p>
        <router-link to="/">
          <a
            href="#"
            class="primary-btn pd-cart mt-3"
            style="background-color: #4C4C49;"
          >Back to Home</a>
        </router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Success",
};
</script>