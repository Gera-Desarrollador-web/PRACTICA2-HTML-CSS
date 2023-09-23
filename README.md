# PRACTICA2-HTML-CSS
Página web donde aplico diferentes estilos de bordes, textos, fondos y animaciones.

![](https://github.com/Gera-Desarrollador-web/PRACTICA2-HTML-CSS/blob/master/assets/img/README.png?raw=true)

<h2>Secciones de la pagina web</h2>
<ul>
<li>Inicio: donde proporciono una breve introducción sobre qué es CSS y algunos enlaces de interés.</li>
<li>Bordes: donde se muestran los diferentes tipos de bordes disponibles en CSS.</li>
<li>Texto: donde se exploran las posibilidades de manipulación del texto mediante CSS.</li>
<li>Fondos: donde se presentan los diversos tipos de fondos que se pueden crear con CSS.</li>
<li>Animaciones: donde se exhiben las distintas animaciones que CSS ofrece.</li>
</ul>

<h2>Algunos conceptos aplicados</h2>

<code>
.cajita {
    margin: 0 25px;
    border: 2px solid black;
    width: 25px;
    height: 25px;
    position: relative;
}
</code>

<code>
  @keyframes ejemplo{
    from{
    left: 0;
    background-color: red;
    }
to{
    left: 250PX;
    background-color: blue;
}
}
h4{
    margin-left: 15px;
}

.linear{
    animation: ejemplo 2s linear infinite alternate;
}
</code>
