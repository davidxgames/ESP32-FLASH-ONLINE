 
 
 
 
 <esp-web-install-button manifest="proyectos/controles_bluetooth/xgames_snes/manifest.json">
 
  <input class="btn" type="button" slot="activate"/>
  <span slot="unsupported">Ah snap, your browser does not support WebSerial API! If you are using a mobile browser, this is expected. Please, move to the desktop version.</span>
  <span slot="not-allowed">Ah snap, you are not allowed to use this on HTTP!</span>
</esp-web-install-button>



<script>
  // preload bg images
  var img1 = new Image();
  var img2 = new Image();
  img1.src="imagenes/pswitch_h.png";
  img2.src="imagenes/pswitch_p.png";
</script>
