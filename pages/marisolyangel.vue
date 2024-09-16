<template>
  <div class="relative  h-screen bg-cover bg-center bg-[url('/assets/images/7.jpg')]">

    <!-- Overlay -->
    <div class="flex flex-col justify-center items-center h-full text-white text-5xl overlay ">
      <div class="h-1/2 flex flex-col  pt-12 animate__animated animate__fadeIn text-amber-50	"
        style="animation-delay: 400ms; animation-duration:900ms;">
        <span class="font1 sh ">SAVE the DATE</span>
        <span class="tangerine-regular sh text-3xl text-center">04.01.25</span>

      </div>
      <div class="h-1/2 flex justify-center items-center">

        <span class="tangerine-regular sh animate__animated animate__fadeIn text-6xl text-amber-50	"
          style="animation-delay: 600ms; animation-duration:900ms;">Marisol & Ángel</span>

      </div>
      <div class="mb-24 animate-bounce " style="animation-duration: 2800ms;">
        <svg class="size-10 " width="100" height="100" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
          <polygon points="50,10 90,50 80,50 50,20 20,50 10,50" fill="white" />
          <polygon points="50,40 90,80 80,80 50,50 20,80 10,80" fill="white" />
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
  <div class="h-96 cormorant-garamond-light  bg-cover h-screen bg-[url('/assets/images/bg.jpg')]">

    <div class="px-12  h-[450px]">
      <p class="text-center text-3xl animate__animated  hidden duration-1000	" style="animation-duration: 1000ms;"
        id="text1">
        Hay momentos en la vida que marcan un antes y un después
      </p>
      <p class="text-center text-3xl hidden animate__animated"
        style="animation-duration: 1200ms; animation-delay: 800ms;" id="text2">
        Nos encantaría que nos acompañaras a celebrar el comienzo de nuestra vida juntos.
      </p>
      <p class="text-center mt-12 hidden animate__animated" style="animation-duration: 1800ms; animation-delay: 1200ms;"
        id="text3">
        <span class="cormorant-garamond-bold-italic text-5xl text-center">NUESTRA BODA</span>

      </p>

      <p></p>


    </div>

    <div class=" text-center">
      <img src="/assets/images/Separador-Premium.png" alt="">

      <div class="  h-96 bg-cover bg-top bg-[url('/assets/images/8.jpg')]  flex items-center">
        <div
          class="grid grid-cols-4 glass text-white text-center w-full rounded-xl mx-4  mt-44 pt-2 animate__animated  hidden"
          id="div1">
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
    <div class="h-16">

      <img class="absolute " src="/assets/images/Separador-Premium.png" alt="">
    </div>

    <div class="flex flex-col text-xl justify-top   bg-cover bg-[url('/assets/images/bg.jpg')]">
      <div class="min-h-[580px]">

      
      <div class="grid text-right  w-full ">
     
        <div class="flex w-full  justify-end items-center   animate__animated hidden" id="div2"
          style="animation-duration: 1200ms;">
          <img class="size-8 mt-6 mr-3" src="/assets/images/calendar-svgrepo-com.svg" alt="">
          <div class="felx items-center h-full">

            <span class="text-8xl text-rigth mr-4">04.01.25</span>
          </div>
        </div>
        <div class="div3  animate__animated hidden" id="div3"
          style="animation-duration: 1200ms; animation-delay: 400ms">

          <span class="mr-4 mt-4">Código de Vestimenta</span> <br>
          <span class="mr-4 ">Elegancia en <span class="font-bold">negro</span>. Atuendo formal.</span>
        </div>

      </div>

      <div class="text-left ml-4 grid mt-12">
        <span class="text-5xl hidden  animate__animated" id="div4" style="animation-duration: 800ms;">Ceremonia</span>
        <div class=" animate__animated hidden" id="div5" style="animation-duration: 1000ms; animation-delay: 400ms;">
          <span class=" text-4xl">04:00</span>
          <span>
            pm
          </span>
        </div>
        <div class=" animate__animated hidden" id="div6" style="animation-duration: 900ms; animation-delay: 700ms;">
          <span class="mr-4  " >DIRECCION // DIRECCION</span> <br>
          <a href="https://maps.app.goo.gl/ijJcEcgQ6x8d9Gj38 " target="_blank"><span class="underline mr-4">Ver
              Ubicacion</span></a>

        </div>
      </div>
      <div class="text-right mr-4 grid mt-12">
        <span class="text-5xl  animate__animated hidden" id="div7" style="animation-duration: 900ms;">Recepción</span>
        <div class=" animate__animated hidden" id="div8" style="animation-duration: 1200; animation-delay: 300ms;">
          <span class=" text-4xl">08:00</span>
          <span class="mr-4">
            pm
          </span>
        </div>
        <div class=" animate__animated hidden" id="div9" style="animation-duration: 500ms; animation-delay: 680ms;">

          <span class="mr-4 ">DIRECCION // DIRECCION</span> <br>
          <a href="https://maps.app.goo.gl/ijJcEcgQ6x8d9Gj38 " target="_blank"><span class="underline mr-4">Ver
              Ubicacion</span></a>
        </div>

      </div>
    </div>

      <div
        class=" min-h-[800px] flex items-end justify-center  bg-center bg-cover  bg-[url('/assets/images/9.jpg')] mt-20">
        <div class="glass py-6 mx-4 my-6 px-4 h-auto w-full   animate__animated hidden" id="div10">
          <h2 class="text-2xl font-bold text-black mb-6 text-center">Confirma tu Asistencia</h2>
          <form @submit.prevent="submitForm">
            <div class="mb-4">
              <label for="name" class="block text-black font-semibold">Nombre</label>
              <input type="text" id="name" v-model="name"
                class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-indigo-500"
                required>
            </div>
            <div class="mb-4">
              <label for="email" class="block text-black font-semibold">Número de celular</label>
              <input type="text" id="email" v-model="number"
                class="w-full px-4 py-2 border border-gray-300 rounded-lg focus:outline-none focus:border-indigo-500"
                required>
            </div>
            <div class="text-center">

              <label class="block text-black font-semibold mb-2 p-8 text-3xl">¿Asistirás?</label>
            </div>
            <div class="flex mb-4">
              <div class="w-full">
                <label class="inline-flex items-center">
                  <input type="checkbox" name="confirm" v-model="attendanceYes"
                    class="form-checkbox h-5 w-5 text-indigo-600" @change="attendanceNo = false">
                  <span class="ml-2">Sí, asistiré</span>
                </label>
              </div>
              <div class=" w-full">
                <label class="inline-flex items-center">
                  <input type="checkbox" name="confirm" v-model="attendanceNo"
                    class="form-checkbox h-5 w-5 text-indigo-600" @change="attendanceYes = false">
                  <span class="ml-2">No, no podré asistir</span>
                </label>
              </div>
            </div>
            <button type="submit"
              class="w-full bg-black text-white py-2 rounded-lg hover:bg-white transition duration-300">Confirmar</button>
          </form>
        </div>
      </div>
      <div class="py-12 mx-4 min-h-96 text-center grid">
        <span>Su compañía es el mejor regalo que podemos recibir.</span>


        <span>Con cariño</span>


        <span>Marisol y Ángel</span>
      </div>
    
    </div>
  </div>

</template>
<script setup>
import 'animate.css';
import { useFetch } from '#app'

import { ref, onMounted, onBeforeUnmount } from 'vue'

const targetDate = new Date('2025-01-01T00:00:00') // Cambia esto a tu fecha objetivo
const days = ref(0)
const hours = ref(0)
const minutes = ref(0)
const seconds = ref(0)


const name = ref('')
const number = ref('')
const attendanceYes = ref(false)
const attendanceNo = ref(false)
const itsPlay = ref(false)
const confirmed =ref('')



const submitForm = async () => {
  try {
    // Construir el objeto de datos para enviar
    confirmed.value = attendanceYes.value ? true : attendanceNo.value ? false : null
    const formData = {
      name: name.value + '%' +  confirmed.value,
      phone: number.value,

    }

    // Validar que se ha marcado alguna opción
    if (formData.confirmed === null) {
      alert('Por favor selecciona si asistirás o no.')
      return
    }

    
    // Enviar la petición POST
    const response = await useFetch('teinvito-b3dkbfewgubvc3e6.southcentralus-01.azurewebsites.net/api/Person', {
      method: 'POST',
      body: formData,
      headers: {
        'Content-Type': 'application/json',
      },
    })

    // Comprobar la respuesta
    if (response.error) {
      console.error('Error al enviar el formulario', response.error)
    } else {
      alert('Formulario enviado correctamente.')
    }
  } catch (error) {
    console.error('Error en la solicitud', error)
  }
}



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




function animationsScroll() {

  return () => {
    let scrollTop = window.scrollY || document.documentElement.scrollTop
    if (scrollTop > 10) {
      if (!itsPlay.value) {
        itsPlay.value = true
        console.log('play' + itsPlay.value)
        const audio = new Audio('/song.mp3') // Ruta del archivo de audio en la carpeta public
        audio.volume = 0.8
        audio.play().catch(error => {
          console.error("Error al reproducir el audio", error)

        })
      }


    }
    console.log(scrollTop)




    if (scrollTop > 450) {
      document.getElementById('text1').classList.remove('hidden')
      document.getElementById('text2').classList.remove('hidden')
      document.getElementById('text3').classList.remove('hidden')
      document.getElementById('text1').classList.add('animate__fadeIn')
      document.getElementById('text2').classList.add('animate__fadeIn')
      document.getElementById('text3').classList.add('animate__fadeIn')
    }
    if (scrollTop > 1100) {
      document.getElementById('div1').classList.remove('hidden')
      document.getElementById('div1').classList.add('animate__fadeIn')

    }
    if (scrollTop > 1500) {
      document.getElementById('div2').classList.remove('hidden')
      document.getElementById('div3').classList.remove('hidden')
      document.getElementById('div2').classList.add('animate__fadeInRight')
      document.getElementById('div3').classList.add('animate__fadeInRight')
    }
    if (scrollTop > 1700) {
      document.getElementById('div4').classList.remove('hidden')
      document.getElementById('div5').classList.remove('hidden')
      document.getElementById('div6').classList.remove('hidden')
      document.getElementById('div4').classList.add('animate__fadeInLeft')
      document.getElementById('div5').classList.add('animate__fadeInLeft')
      document.getElementById('div6').classList.add('animate__fadeInLeft')
    }
    if (scrollTop > 1900) {
      document.getElementById('div7').classList.remove('hidden')
      document.getElementById('div8').classList.remove('hidden')
      document.getElementById('div9').classList.remove('hidden')
      document.getElementById('div7').classList.add('animate__fadeInRight')
      document.getElementById('div8').classList.add('animate__fadeInRight')
      document.getElementById('div9').classList.add('animate__fadeInRight')
    }
    if (scrollTop >2200) {
      document.getElementById('div10').classList.remove('hidden')
      
      document.getElementById('div10').classList.add('animate__fadeInDown')
      
    }

    

  }
}


onMounted(() => {
  calculateTimeLeft()
  interval = setInterval(calculateTimeLeft, 1000)




  const onScroll = animationsScroll()
  window.addEventListener('scroll', onScroll)
  onUnmounted(() => {
    window.removeEventListener('scroll', onScroll)
  })

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
  background: rgba(214, 214, 214, 0.616);
  box-shadow: 0 8px 32px 0 rgba(0, 0, 0, 0.911);
  backdrop-filter: blur(3px);
  -webkit-backdrop-filter: blur(3px);
  border-radius: 10px;
  border: 1px solid rgba(29, 29, 29, 0.178);
}
</style>