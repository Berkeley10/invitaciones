<template>
  <div class="relative  h-screen bg-cover bg-center bg-[url('/assets/images/3.jpg')]">

    <!-- Overlay -->
    <div class="flex flex-col justify-center items-center h-full text-white text-5xl overlay ">
      <div class="h-1/2 flex flex-col  pt-12 animate__animated animate__fadeIn"
        style="animation-delay: 400ms; animation-duration:900ms;">
        <span class="font1 sh ">SAVE the DATE</span>
        <span class="font2 sh text-3xl text-center">04.01.25</span>

      </div>
      <div class="h-1/2 flex justify-center items-center">

        <span class="font2 sh animate__animated animate__fadeIn text-3xl"
          style="animation-delay: 600ms; animation-duration:900ms;">Marisol y Ángel</span>

      </div>
      <div class="mb-24 animate-bounce " style="animation-duration: 2800ms;">
        <svg class="size-10 " width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
  <polygon points="50,10 90,50 80,50 50,20 20,50 10,50" fill="white"/>
  <polygon points="50,40 90,80 80,80 50,50 20,80 10,80" fill="white"/>
</svg>

      </div>
    </div>
    <!-- Contenido dentro del div -->
    <div class="relative z-10">
      <!-- Aquí va tu contenido -->
    </div>
  </div>
  <div class=" w-full">
    <img src="/assets/images/Separador-Premium.png" alt="">
  </div>
  <div class=" cormorant-garamond-light  bg-cover h-screen bg-[url('/assets/images/bg.jpg')]">

    <div class="px-12">
      <p class="text-center text-3xl">
        Hay momentos en la vida que marcan un antes y un después
      </p>
      <p class="text-center text-3xl">
        Nos encantaría que nos acompañaras a celebrar el comienzo de nuestra vida juntos.
      </p>
      <p class="text-center mt-12">
        <span class="cormorant-garamond-bold-italic text-5xl text-center">NUESTRA BODA</span>

      </p>

      <p></p>


    </div>

    <div class=" text-center">
      <img src="/assets/images/Separador-Premium.png" alt="">

      <div class="  h-96 bg-cover bg-top bg-[url('/assets/images/4.jpg')]  flex items-center">
        <div class="grid grid-cols-4 glass text-white text-center h-suto  w-full rounded-xl mx-4  mt-44 pt-2">
          <div class="col-span-4 sh"> <span class="text-5xl">Faltan</span>

          </div>

          <div class="flex flex-col sh">
            <span class="text-4xl sh"> {{ days }}
            </span>
            <span>D</span>
          </div>
          <div class="flex flex-col">
            <span class="text-4xl sh"> {{ hours }}
            </span>
            <span>H</span>
          </div>
          <div class="flex flex-col sh">
            <span class="text-4xl"> {{ minutes }}
            </span>
            <span>M</span>
          </div>
          <div class="flex flex-col sh">
            <span class="text-4xl"> {{ seconds }}
            </span>
            <span>S</span>
          </div>
        </div>
      </div>
    </div>
    <img src="/assets/images/Separador-Premium.png" alt="">

    <div class="flex flex-col text-xl justify-top h-screen bg-cover bg-[url('/assets/images/bg.jpg')]">
      <div class="grid text-right  w-full">
        <div>

          <!-- <img src="/assets/images/cal.png" alt="" class="max-w-12"> -->
        </div>
        <!-- <span class="text-4xl cormorant-garamond-bold-italic text-center pt-12">
          FECHA
        </span> -->
        <span class="text-8xl text-rigth mr-4">04.01.25</span>
        <span class="mr-4 mt-4">Código de Vestimenta</span>
        <span class="mr-4 ">Elegancia en <span class="font-bold">negro</span>. Atuendo formal.</span>

      </div>

      <div class="text-left ml-4 grid mt-12">
        <span class="text-5xl">Ceremonia</span>
        <div>
          <span class=" text-4xl">04:00</span>
          <span>
            pm
          </span>
        </div>
        <span class="mr-4 ">DIRECCION // DIRECCION</span>
        <a href=""><span class="underline mr-4">Ver Ubicacion</span></a>

      </div>
      <div class="text-right mr-4 grid mt-12">
        <span class="text-5xl">Recepción</span>
        <div>
          <span class=" text-4xl">08:00</span>
          <span class="mr-4">
            pm
          </span>
        </div>
        <span class="mr-4 ">DIRECCION // DIRECCION</span>
        <a href=""><span class="underline mr-4">Ver Ubicacion</span></a>

      </div>


      <!-- <div class="mt-24">
        <div>
          <span>CEREMONIA</span>
        </div>
        <svg class="size-20" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 576 512">
          <path
          d="M408 120c0 54.6-73.1 151.9-105.2 192c-7.7 9.6-22 9.6-29.6 0C241.1 271.9 168 174.6 168 120C168 53.7 221.7 0 288 0s120 53.7 120 120zm8 80.4c3.5-6.9 6.7-13.8 9.6-20.6c.5-1.2 1-2.5 1.5-3.7l116-46.4C558.9 123.4 576 135 576 152l0 270.8c0 9.8-6 18.6-15.1 22.3L416 503l0-302.6zM137.6 138.3c2.4 14.1 7.2 28.3 12.8 41.5c2.9 6.8 6.1 13.7 9.6 20.6l0 251.4L32.9 502.7C17.1 509 0 497.4 0 480.4L0 209.6c0-9.8 6-18.6 15.1-22.3l122.6-49zM327.8 332c13.9-17.4 35.7-45.7 56.2-77l0 249.3L192 449.4 192 255c20.5 31.3 42.3 59.6 56.2 77c20.5 25.6 59.1 25.6 79.6 0zM288 152a40 40 0 1 0 0-80 40 40 0 1 0 0 80z" />
        </svg>
        
      </div> -->
    </div>
  </div>

</template>
<script setup>
import 'animate.css';

import { ref, onMounted, onBeforeUnmount } from 'vue'

const targetDate = new Date('2025-01-01T00:00:00') // Cambia esto a tu fecha objetivo
const days = ref(0)
const hours = ref(0)
const minutes = ref(0)
const seconds = ref(0)

const calculateTimeLeft = () => {
  const now = new Date()
  const timeDifference = targetDate - now

  if (timeDifference > 0) {
    days.value = Math.floor(timeDifference / (1000 * 60 * 60 * 24))
    hours.value = Math.floor((timeDifference % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60))
    minutes.value = Math.floor((timeDifference % (1000 * 60 * 60)) / (1000 * 60))
    seconds.value = Math.floor((timeDifference % (1000 * 60)) / 1000)
  } else {
    days.value = 0
    hours.value = 0
    minutes.value = 0
    seconds.value = 0
  }
}

let interval = null

onMounted(() => {
  calculateTimeLeft()
  interval = setInterval(calculateTimeLeft, 1000)
})

onBeforeUnmount(() => {
  clearInterval(interval)
})
</script>
<style scoped>
.overlay {
  background: rgba(0, 0, 0, 0.452);
  box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37);
  backdrop-filter: blur(0px);
  -webkit-backdrop-filter: blur(0px);

  border: 1px solid rgba(255, 255, 255, 0.18);
}

.sh {
  text-shadow: 0px 0px 20px rgb(0, 0, 0);
}

.glass {
  background: rgba(51, 51, 51, 0.384);
  box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.911);
  backdrop-filter: blur(5px);
  -webkit-backdrop-filter: blur(5px);
  border-radius: 10px;
  border: 1px solid rgba(29, 29, 29, 0.178);
}
</style>