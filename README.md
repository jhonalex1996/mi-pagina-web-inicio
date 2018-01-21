<!DOCTYPE html>
<html>
<head>
<meta charset="iso-8859-1"/>
<meta name="description" content="desarrollo web"/>
<meta name="keywords" content="desarrollo web,html 5,javascrypt,css"/>
<title>desarrollo de paginas web</title>
<link rel="stylesheet" href="mihojadeestilos.css"/>
<script src="codigoscript"></script>
<style media="screen">
  #principal{
    width: 260px;
    /*background-color:#0026ec;*/
    text-align: center;
    margin: 15px auto;
    padding: 12px;
    border: 5px  solid rgb(6, 6, 6);
    border-radius: 50px 60px 15px;/*define los bordes del titulo de la pagina*/
    box-shadow:rgba(219, 215, 211, 0.83) 5px 5px 15px;
    background: -moz-linear-gradient(top,#0222f4,#12bdee);/*hace un degradado en el titulo de pagina de azul a un azul mas claro*/
    background: -webkit-linear-gradient(top,#020cf5,#2f96f6);
    background: -ms-linear-gradient(top,#0222f4,#12bdee);
/*  -webkit-transform:rotate(8deg);/*debe de girar el titulo*/
}
    #titulo{
      font: bold 15px algerian,verdana , sans-serif;
      text-shadow: rgb(156, 172, 151) 5px 3px 2px;
    }
</style>

</head>
<body>
  <figure id="foto">
    <img src="imagenes/images1.jpg" alt="lineas de codigo html"/>
  </figure>
  <header id="principal">
  <span id="titulo"><h1 id="titulo">desarrollo web j.g</h1></span>
  </header>
  <nav id="barranavegacion">
    <ul>
      <li>inicio</li>
    <li>quienes somos</li>
    <li>mision</li>
    <li>vision</li>
    <li>contactanos</li>
  </ul>
</nav>
<aside id="barralateral">
  <p class="importante">nuestro portafolio</p>
  <p>precios</p>
  <p class="importante">diseno sitio web personalizado</p>
  <p>seo</p>
</aside>
<section id="contenidoprincipal">
  <article>
  <blockquote>en esta seccion te explicaremos en forma breve como trabajamos no solo hace falta tener un sitio web,
    tambien hace falta un <strong>diseno personalizado</strong> que capte la atencion de los usuarios y tambien el <em>posicionamiento</em> nos enfocamos en estos dos puntos
    para que tengas tu sitio apto atraer clientes</blockquote>
    <footer>
      <p><mark>comentarios de usuarios</mark></p>
    </footer>
  </article>
</section>
<footer id="piedepagina"><small>derechos reservados para <cite>jhonatan alexander grajales medina</cite></small>
<address>llamanos al 319 363 6323</address>
</body>
</html>
