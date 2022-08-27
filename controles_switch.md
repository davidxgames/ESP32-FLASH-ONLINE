[PAGINA PRINCIPAL](index.md)

# CONTROLES SWITCH DIY

<img src="imagenes/controles_switch.png"
height="200">

En este proyecto aprenderemos a convertir nuestros controles en controles compatibbes con nuestro nintendo switch.
Este proyecto esta basado en el trabajo de [mitchellcairns](https://github.com/mitchellcairns)

Y quiero agradecer a Ervin Olvera por ayudarme a terminar este proyecto.

### Nuestro primer control sera el de SNES

<img src="imagenes/CONTROLsnes.png"
height="150">

###### FIRMWARE DONDE DEBES AGREGAR BOTONES EXTRAS

<script type="module" src="web/install-button.js?module">conectar</script>
<esp-web-install-button manifest="proyectos/controles_switch/snes/manifest.json"></esp-web-install-button>

### ----------------------------

###### FIRMWARE DONDE NO DEBES AGREGAR BOTONES EXTRAS
###### SELECT+L=ZL y SELECT+R=ZR

<script type="module" src="web/install-button.js?module">conectar</script>
<esp-web-install-button manifest="proyectos/controles_switch/snes_no_botones/manifest.json"></esp-web-install-button>




<img src="imagenes/dividir.jpg"
height="20">

### Nuestro segundo control sera el de N64

<img src="imagenes/n64.png"
height="150">

<script type="module" src="web/install-button.js?module">conectar</script>
<esp-web-install-button manifest="proyectos/controles_switch/n64/manifest.json"></esp-web-install-button>

<img src="imagenes/dividir.jpg"
height="20">

### Nuestro tercer control sera el de NES

<img src="imagenes/nes.png"
height="150">

###### Con este firmware tu control sera detectado como control de NES



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





###### Con este firmware tu control sera detectado como control de FAMICON
<script type="module" src="web/install-button.js?module">conectar</script>
<esp-web-install-button manifest="proyectos/controles_switch/fc/manifest.json"></esp-web-install-button>

<img src="imagenes/dividir.jpg"
height="20">

### Nuestro cuarto control sera el de PS1

<img src="imagenes/PS1.png"
height="150">

<script type="module" src="web/install-button.js?module">conectar</script>
<esp-web-install-button manifest="proyectos/controles_switch/ps1/manifest.json"></esp-web-install-button>

<img src="imagenes/dividir.jpg"
height="20">
