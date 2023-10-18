<template>
  <FadeInContainer>
    <section class="ui container bio">
      <div>
        <h2>Quienes somos
        </h2>
        <p>Somos el CDE Baloncesto Pumas y comenzamos nuestra trayectoria en el distrito de Chamartín, Madrid, en el Colegio Pintor Rosales en el año 2012. Desde 2016, hemos estado trabajando en colaboración con los Colegios Reina Victoria y Amador de los Ríos, compitiendo en los <a href="https://www.madrid.es/portales/munimadrid/es/Inicio/Cultura-ocio-y-deporte/Deporte/Competiciones-deportivas-municipales-2023-2024/?vgnextfmt=default&vgnextoid=3272bdf3ca5b2810VgnVCM1000001d4a900aRCRD&vgnextchannel=c7a8efff228fe410VgnVCM2000000c205a0aRCRD&idCapitulo=11749137" target="_blank" rel="noopener">Juegos Deportivos Municipales (JDM).</a></p>
        <div>
          <div class="bio-item">
            <div>
              <i class="basketball ball icon"></i>
            </div>
            <div>
              <div>
                <h4>Filosofía</h4>
              </div>
              <p>Nuestra filosofía en nuestras escuelas se centra en la educación basada en los valores del respeto, la tolerancia y la responsabilidad, mientras fomentamos el amor por este deporte. Es fundamental que nuestros niños disfruten mientras aprenden, al tiempo que les enseñamos a trabajar en equipo, a ser disciplinados y a cultivar una actitud positiva</p>
            </div>
          </div>
          <div class="bio-item">
            <div>
              <i class="users icon"></i>
            </div>
            <div>
              <div>
                <h4> Colaboración en Nuestra Comunidad de Baloncesto</h4>
              </div>
              <p>Descubre cómo colaborar de manera efectiva en nuestra comunidad de baloncesto, fomentando el respeto y la colaboración. <a href="/nuestra-comunidad">Más información</a></p>
            </div>
          </div>
        </div>
      </div>
      <div class="img-container">
        <img src="/images/pumas/team-together.jfif" alt="basketball court">
      </div>
    </section>
  </FadeInContainer>
</template>
<style lang="scss" scoped>
.bio {
  margin-bottom: 5em;
  @include desktop {
    display: flex;
    gap: 20px;
  }
  .bio-item {
    display: flex;
    justify-content: space-between;
    gap: 20px;
    margin: 2.2em 0 0 0;

    i {
      font-size: 2.5rem;
      color: $primary;
    }
  }

  .img-container {
    background: $black;
    background: linear-gradient(135deg, $black 0%, $primary 100%);
    padding: 1em;

    @include desktop {
      width: 70%;
    }

    img {
      width: 100%;
      filter: brightness(115%) contrast(100%) saturate(0%) blur(0px) hue-rotate(0deg);
    }
  }
}
</style>
