[PAGINA PRINCIPAL](index.md)

# CONTROLES BLUEGAMEPAD

<img src="imagenes/controles_switch.png"
height="200">

En este proyecto aprenderemos a convertir nuestros controles en controles compatibbes con nuestro nintendo switch.
Este proyecto esta basado en el trabajo de [mitchellcairns](https://github.com/mitchellcairns)

Y quiero agradecer a Ervin Olvera por ayudarme a terminar este proyecto.

### Nuestro primer control sera el de N64

<img src="imagenes/n64.png"
height="150">



 <esp-web-install-button manifest="proyectos/controles_switch/nes/manifest.json">
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
height="20">

