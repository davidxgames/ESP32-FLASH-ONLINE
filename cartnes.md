[PAGINA PRINCIPAL](index.md)

# NES Label Slider 4" LCD TFT con ESP32



<p align="center">
 <img src="imagenes/cartucho.gif"
height="250">
</p>

Camaradas este proyecto tiene años que lo quiero hacer, pero hoy por fin lo logre, y lo programadado yo!! desde cero? claro que no!!
Use la mejor libreria de arduino para utilizar pantallas y es "Arduino GFX" y su su creador es @moononournation (https://github.com/moononournation) tan facil de usar es que alguien como yo que no estudio nada de programacion, la pudo usar!!

Tambien quiero agradecer como siempre al camarada Ervig Olvera que pronto nos sorprendera con algo nuevo. Tambien al camarada Jorge Belman quien se afrecio ayudarme con la edicion de las imagenes, gracias camarada!!!

Y hoy, estrenamos boton para flashear nuestro esp32, un POWER SWITCH!!! y que mejor forma de empezar a usarlo con un proyecto tan nintendero como este.




 <esp-web-install-button manifest="proyectos/diy/cartucho_nes/manifest.json"> 
  <script type="module" src="web/install-button.js?module">conectar</script>
  <input class="btn" type="button" slot="activate"/>
  <span slot="unsupported">Ah snap, your browser does not support WebSerial API! If you are using a mobile browser, this is expected. Please, move to the desktop version.</span>
  <span slot="not-allowed">Ah snap, you are not allowed to use this on HTTP!</span>
</esp-web-install-button>

<p align="center">Usa este power switch con precaucion.</p>




<script>
  // preload bg images
  var img1 = new Image();
  var img2 = new Image();
  img1.src="pswitch_h.png";
  img2.src="pswitch_p.png";
</script>



