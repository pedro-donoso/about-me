<template>
  <div id="card">
    <div class="card__title">
      <div class="card__content">
        <h5>Pedro Donoso - Front-end Developer</h5>
      </div>
    </div>

    <div class="card__description">

<h5>Experiencia</h5>
<br>

  <h6>Programa Talento Digital (2020)</h6>
<h5>Front-end Developer VueJS :</h5>
<p class="card__content">Bootcamp de Desarrollo realizado en conjunto por Academia Desafío Latam y Cámara de Comercio de Santiago, sobre Fundamentos Web, CSS Avanzado, Programación con JavaScript, Fundamentos de componentes con Vue JS, entre otras habilidades de Programación.</p>

<h6>Universidad de Santiago de Chile (2019)</h6>
<h5>Investigador Smart Cities :</h5>
<p class="card__content">Área de Investigación Tesis, “La aportación de la Ingeniería en Geomensura y el Análisis de Big Data al desarrollo de Ciudades Inteligentes (Smart Cities).</p>

<h6>Oficina Catastro Lo Prado (2016-2018)</h6>
<h5>Administrador GIS</h5>
<p class="card__content">Encargado de realizar Webmapping con Arc Gis y software libre QGIS sobre: Seguridad, Áreas verdes, Tránsito, Comercio. Equipo logra desarrollar plataforma web para visualizaciones de sectores vulnerables para gestionar soluciones y planes sociales para mejorar distribución de recursos.</p>

<hr>

<h5>Habilidades Programación</h5>

      <table class="table table-dark">
        <thead>
          <tr>
            <th scope="col">HTML</th>
            <th scope="col">CSS</th>
            <th scope="col">JavaScript</th>
          </tr>
        </thead>
        <tbody>
          <tr>
              <th scope="col">Git</th>
            <th scope="col">Vue JS</th>
            <th scope="col">Terminal</th>
          </tr>
          <tr>
             <th scope="col">APIs</th>
            <th scope="col">Bootstrap</th>
            <th scope="col">Firebase</th>
          </tr>
          <tr>
             <th scope="col">Flexbox</th>
            <th scope="col">Sass</th>
            <th scope="col">MongoDB</th>
          </tr>
        </tbody>
      </table>

      <hr>

      <h5>Formación</h5>
<ul>
  
</ul>

<h6>Universidad de Santiago de Chile (2016-2020)</h6>
<h5>Geomensura</h5>

<h6>Universidad de las Américas (2006-2009)</h6>
<h5>Topografía</h5>

<h6>Centro Educacional San Mateo (2002-2005)</h6>
<h5>Dibujante Técnico</h5>

    </div>
  </div>
</template>

<style lang="scss" scoped>
#card {
  font-family: "Montserrat", sans-serif;
  margin: 0.5rem;
  background: rgb(36, 77, 167);
  padding: 0.5rem;
  border-radius: 0.5rem;
  color: #fff;
  width: 100%;
}

.card__title {
  display: flex;
  align-items: center;
  background: #222;
  border-radius: 0.5rem;
}

.card__content{
padding: 0.5rem;
text-align: justify;
}



.card__description {
  line-height: 1rem;
  margin: 1rem auto;
}

.table {
  width: 100%;
  border-spacing: 0;

  tr,
  th,
  tr,
  td {
    border: 1px solid #fff;
    border-top: none;
    padding: 0.5rem;
    text-align: center;
  }
}
</style>