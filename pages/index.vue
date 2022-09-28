<template>
  <div>
    <Navbar />
    <div class="container">
      <div style="width:100%;height:0px;position:relative;padding-bottom:55.000%;" class="mt-3 rounded"><iframe src="https://streamable.com/e/yss0ya?autoplay=1" frameborder="0" width="100%" height="100%" allowfullscreen allow="autoplay" style="width:100%;height:100%;position:absolute;left:0px;top:0px;overflow:hidden;" class="rounded"></iframe></div>
      <div class="my-3">
        <b-card no-body class="overflow-hidden">
          <b-row no-gutters>
            <b-col md="6">
              <b-card-img
                src="/expotransporte.jpg"
                alt="Image"
                class="rounded-0"
              ></b-card-img>
            </b-col>
            <b-col md="6">
              <b-card-body>
                  <h2 class="mb-3">8 al 11 de Diciembre del 2022</h2>
                  <h4 class="mb-3">Parque Simón Bolívar, La Carlota<br>Estado Miranda</h4>
                  <p>Un gran evento de encuentro para todo el transporte acuático (Marítimo, Fluvial, y Submarino), Aéreo, Aeroespacial y Terrestre.</p>
              </b-card-body>
            </b-col>
          </b-row>
        </b-card>
      </div>
      <a href="http://www.mppt.gob.ve/" target="_blank">
      <b-img src="/logo_ministerio.jpg" fluid alt="Green Show Production" class="mx-auto d-block p-4"></b-img>
      </a>
    </div>
    <Footer />
  </div>
</template>

<script>
import Navbar from "~/components/Navbar.vue";
import Footer from "~/components/Footer.vue";
export default {
  name: "IndexPage",
  components: { Navbar, Footer },
};
</script>
