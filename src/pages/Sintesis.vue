<template>
  <div class="curso-main-container pb-3">
    <BannerInterno icono="fas fa-sitemap" titulo="Síntesis"></BannerInterno>
    <div class="container tarjeta tarjeta--blanca p-4 p-md-5">
      <p class="mb-5" data-aos="fade-down" data-aos-duration="800">
        El diagrama siguiente representa la estructura integral del componente
        formativo, donde se parte del concepto central de gestión avanzada de
        datos para IA y se ramifica en cuatro áreas fundamentales: modelamiento
        avanzado, inteligencia de negocios, análisis exploratorio y preparación
        avanzada. Cada una de estas áreas se desglosa en subtemas específicos
        que constituyen los pilares del proceso de integración y gestión de
        datos para IA.
      </p>
      <div class="row mb-5">
        <div class="col-lg mb-4 mb-lg-0" data-aos="zoom-in">
          <div
            class="p-4 h-100 d-flex align-content-center flex-wrap"
            style="background-color:#ECF2FF;border-radius:10px;"
          >
            <p class="mb-0">
              Esta organización refleja la progresión lógica del aprendizaje,
              desde los fundamentos del modelamiento hasta las técnicas más
              avanzadas de preparación de datos. La interconexión entre las
              diferentes áreas ilustra cómo cada concepto contribuye al objetivo
              final de preparar datos de alta calidad para su uso en sistemas de
              inteligencia artificial.
            </p>
          </div>
        </div>
        <div class="col-lg mb-4 mb-lg-0 d-none d-lg-block" data-aos="zoom-in">
          <figure><img src="@/assets/curso/sintesis1.png" /></figure>
        </div>
        <div class="col-lg mb-4 mb-lg-0" data-aos="zoom-in">
          <div
            class="p-4 h-100 d-flex align-content-center flex-wrap"
            style="background-color:#BDE9FC;border-radius:10px;"
          >
            <p class="mb-0">
              El diagrama sirve como una guía visual para navegar por los
              conceptos presentados en el texto, permitiendo al aprendiz
              comprender rápidamente la estructura del componente y las
              relaciones entre sus diferentes elementos. Se recomienda
              utilizarlo como referencia para organizar el estudio y comprender
              la integración de los diferentes aspectos de la gestión avanzada
              de datos.
            </p>
          </div>
        </div>
      </div>
      <div
        class="row justify-content-center p-4"
        style="background-color:#F4F4F4;border-radius:20px;"
      >
        <div class="col-lg-10 mb-5">
          <figure data-aos="zoom-in-up" data-aos-duration="950">
            <img
              src="@/assets/curso/sintesis.svg"
              alt="Se denomina «Síntesis temática del componente», allí se mencionan los principales temas tratados sobre integración y gestión avanzada de datos para inteligencia artificial —como el modelamiento avanzado, la inteligencia de negocios, el análisis exploratorio y la preparación avanzada de datos— y algunos subtemas que los integran."
            />
          </figure>
        </div>
        <div class="col-auto">
          <a
            class="anexo mb-5"
            :href="obtenerLink('/downloads/Sintesis.pdf')"
            target="_blank"
          >
            <div class="anexo__icono">
              <img src="@/assets/bullets/icono-pdf.svg" />
            </div>
            <div class="anexo__texto">
              <p>Anexo. Síntesis</p>
            </div></a
          >
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'Sintesis',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
