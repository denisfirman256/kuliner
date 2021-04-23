<template>
  <div class="pesanan-sukses">
    <navbar />
    <div class="container">
      <div class="row justify-content-center mt-5">
        <div class="col text-center">
          <img src="../assets/images/menunggu.png" width="300" alt="" />
          <h2><strong>Sukses!!</strong></h2>
          <h4>
            Pesanan anda segera diproses <br />
            Silahkan ditunggu...
          </h4>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import navbar from "@/components/navbar.vue";
export default {
  name: "PesananSukses",
  components: {
    navbar,
  },
};
</script>

<style>
</style>