[PAGINA PRINCIPAL](index.md)

# NES Label Slider 4" LCD TFT con ESP32



<p align="center">
 <img src="imagenes/cartucho.gif"
height="250">
</p>

Camaradas este proyecto tiene años que lo quiero hacer, pero hoy por fin lo logre, y lo e programado yo!! desde cero? claro que no!!
Use la mejor librería de arduino para utilizar pantallas y es "Arduino GFX" y su su creador es @moononournation (https://github.com/moononournation) tan facil de usar es que alguien como yo que no estudio nada de programación, la pudo usar!!

Tambien quiero agradecer como siempre al camarada Ervig Olvera que pronto nos sorprenderá con algo nuevo. También al camarada Jorge Belman quien se ofreció ayudarme con la edición de las imágenes, gracias camarada!!!

Y hoy, estrenamos botón para flashear nuestro esp32, un POWER SWITCH!!! y que mejor forma de empezar a usarlo con un proyecto tan nintendero como este.


 <esp-web-install-button manifest="proyectos/varios/nescart/manifest.json">
 
  <script type="module" src="web/install-button.js?module"></script>
  <input class="btn" type="button" slot="activate"/>
  <span slot="unsupported">Ah snap, your browser does not support WebSerial API! If you are using a mobile browser, this is expected. Please, move to the desktop version.</span>
  <span slot="not-allowed">Ah snap, you are not allowed to use this on HTTP!</span>
</esp-web-install-button>
<p align="center">
Usa este POWER SWITCH con responsabilidad.
</p>



<script>
  // preload bg images
  var img1 = new Image();
  var img2 = new Image();
  img1.src="pswitch_h.png";
  img2.src="pswitch_p.png";
</script>

<img src="imagenes/dividir.jpg"
height="20"><img src="imagenes/dividir.jpg"
height="20">



# NCAT



<p align="center">
 <img src="imagenes/ncat.png"
height="250">
</p>

Hace algunos años, vi un proyecto donde usaban un control de SNES y metian dentro una PI ZERO con una pantalla, compre todo lo necesario, pero al igual como me paso con el NES LABEL SLIDER, prefiero hacerlo con materiales mas baratos para que mas se animen a hacerlo. Asi que me decidi por el proyecto de NATHALISLIGTH el [NCAT](https://github.com/nathalislight/NCAT)


 <esp-web-install-button manifest="proyectos/varios/ncat/manifest.json">
 
  <script type="module" src="web/install-button.js?module"></script>
  <input class="btn" type="button" slot="activate"/>
  <span slot="unsupported">Ah snap, your browser does not support WebSerial API! If you are using a mobile browser, this is expected. Please, move to the desktop version.</span>
  <span slot="not-allowed">Ah snap, you are not allowed to use this on HTTP!</span>
</esp-web-install-button>
<p align="center">
Usa este POWER SWITCH con responsabilidad.
</p>
