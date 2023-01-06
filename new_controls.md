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

