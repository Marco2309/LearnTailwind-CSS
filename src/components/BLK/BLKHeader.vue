<script setup>
import userIcon from "../img/user.vue";
</script>
<template>
  <header class="bg-black text-white">
    <div class="container mx-auto">
      <nav class="flex justify-between pt-5">
        <!-- login -->
        <div class="flex items-center">
          <userIcon class="h-5 w-5" />
          <span class="ml-2">Inicio de sesion</span>
        </div>
        <!-- social media -->
        <div class="flex items-center">
          <img
            class="h-5 w-5"
            src="../../assets/imagenes_blk/link.png"
            alt="link icon"
          />
          <img
            class="h-5 w-5"
            src="../../assets/imagenes_blk/Twitter.png"
            alt="twitter icon"
          />
          <img
            class="h-5 w-5"
            src="../../assets/imagenes_blk/Facebook.png"
            alt="facebook icon"
          />
          <img
            class="h-5 w-5"
            src="../../assets/imagenes_blk/Instagram.png"
            alt="instagram icon"
          />
          <img
            class="h-5 w-5"
            src="../../assets/imagenes_blk/YouTube.png"
            alt="youtube icon"
          />
          <img
            class="h-5 w-5"
            src="../../assets/imagenes_blk/Google Places.png"
            alt="google mapas icon"
          />
        </div>
      </nav>
      <figure class="w-60 mx-auto flex flex-col items-center">
        <img src="../../assets/imagenes_blk/LOGO_BLK.webp" alt="BLK Logo" />
        <figcaption>Nosotros lo hacemos por usted...</figcaption>
      </figure>
      <nav class="flex justify-between mt-10">
        <p>Inicio</p>
        <p>Acerca de</p>
        <p>Servicios</p>
        <p>Calzado Táctico e Industrial</p>
        <p>Reciba una cotización</p>
        <p>Comprar</p>
        <p>Contacto</p>
        <p>Blog</p>
        <p>Más</p>
      </nav>
    </div>
  </header>
</template>
