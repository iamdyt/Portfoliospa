<template>
     <main class="flex-grow">
        <!-- first section -->
        <div class=" lg:px-64 px-12 pt-12 lg:inline-flex mb-4">
          <div class="">
            <p class="text-xl lg:text-4xl text-blue-700 font-bold lg:font-medium uppercase">01.  meet me</p>
            <p class="text-justify lg:text-lg text-grey-darker">I am Lanre Olanlokun, a software developer based in Abeokuta, Nigeria. As a kid I have always wanted to be a Code Ninja. Growing up, I develop a penchant for software development & problem solving, and have written codes ranging from simple todos to complex applications.</p>
            <p class="text-justify lg:text-lg text-gray-darker"> As a computer science graduate, and a member of <span class='italic bg-white'>Programmers Den.</span> I have been part of others to build small and medium sized projects thereby building up my skills. </p>
          </div>

          <div class="w-full">
            <div class="bg-white border-t-8 rounded-lg border-blue-700 lg:ml-16">
              <img src="/svgs/author.png" class="object-contain mb-4" alt="">
              <span class="lg:ml-8 ml-16 "><a href="https://github.com/iamdyt"><i class="fab fa-github text-3xl text-gray-900" aria-hidden="true"></i></a></span>
              <span class="ml-8"><a href="https://twitter.com/iamdytz"><i class="fab fa-twitter text-3xl text-gray-900" aria-hidden="true"></i></a></span>
            </div>
            
          </div>

        </div>

        <!-- second section -->
        <p class="text-xl lg:text-4xl lg:ml-64 ml-10 lg:mt-4 text-blue-700 font-bold lg:font-medium uppercase">02.  featured projects</p>
        <div class="bg-gray-100  lg:px-64 px-12 pt-12 lg:inline-flex pb-1">
          <!-- first project -->
          <div class="lg:w-1/2 mb-4">  
          <div class=" bg-white pulse shadow-lg w-full p-4 ">
            <img src="/svgs/EagleExchange.jpg" class="object-contain" alt="">
            <p class="lg:text-lg text-justify "> A landing Page for Eaglexchange Digital and Cryptocurrency trading platform, responsive, mobile-ready and intuitive.</p>
            <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="http://www.eaglexchange.com.ng">visit&RightArrow;</a></span>
            <span class="rounded-full bg-green-900 px-4 py-1 text-white uppercase">Completed</span>
          </div>
          </div>
          <!-- second project -->
          <div class="lg:w-1/2 ml-4 ">
            <div class=" bg-white shadow-lg w-full p-4 ">
              <img src="/svgs/eazypay.png" class="object-contain" alt="">
              <p class="lg:text-lg text-justify "> EazyPay Payment and Fees remittance Portal. A Platform for seamless Payment and remittance for Tertiary Institutions </p>
              <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="https://eazypay.com.ng">visit&RightArrow;</a></span>
              <span class="rounded-full bg-green-900 px-4 py-1 text-white uppercase">Completed</span>
            </div>
          </div>
        </div>

        <!-- third row -->
        <div class="bg-gray-100  lg:px-64 px-12 pt-12 lg:inline-flex pb-1">
          <!-- third project -->
          <div class="lg:w-1/2 mb-4">  
            <div class=" bg-white shadow-lg w-full p-4 ">
              <img src="/svgs/kontagora.png" class="object-contain" alt="">
              <p class="lg:text-lg text-justify ">The Federal College of Education, Kontagora - Redevelopment of Institution CMS Portal according to TETFUND Specifications.</p>
              <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="http://home.fcekg.edu.ng" target="_blank">visit&RightArrow;</a></span>
              <span class="rounded-full bg-green-900 px-4 py-1 text-white uppercase">Completed</span>
            </div>
            </div>

          <!-- second project -->
          <div class="lg:w-1/2 ml-4 ">
            <div class=" bg-white shadow-lg w-full p-4 ">
              <img src="/svgs/agromint.png" class="object-contain" alt="">
              <p class="lg:text-lg text-justify "> Agromint -  Agromint is revolutionary Agricultural ecommerce platform in Ibadan for buying and selling of agricultural inputs. </p>
              <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="http://agromint.com" target="_blank">visit&RightArrow;</a></span>
              <span class="rounded-full bg-red-900 px-4 py-1 text-white uppercase">Work in Progress</span>
            </div>
          </div>

        </div>

      <!-- Fourth row -->
        <div class="bg-gray-100  lg:px-64 px-12 pt-12 lg:inline-flex pb-1">
          <!-- third project -->
          <div class="lg:w-1/2 mb-4">  
          <div class=" bg-white shadow-lg w-full p-4 ">
            <img src="/svgs/africure.png" class="object-contain" alt="">
            <p class="lg:text-lg text-justify ">Africure - The Curezone for Africa, a platform to discuss Holistic, and Alternative approach to cure terminal diseases</p>
            <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="http://evening-plateau-35380.herokuapp.com/" target="_blank">visit&RightArrow;</a></span>
            <span class="rounded-full bg-green-900 px-4 py-1 text-white uppercase">Completed</span>
          </div>
          </div>
          <!-- second project -->
          <div class="lg:w-1/2 ml-4 ">
            <div class=" bg-white shadow-lg w-full p-4 ">
              <img src="/svgs/translate.png" class="object-contain" alt="">
              <p class="lg:text-lg text-justify "> GoogleTranslate Wrap around Application Programming Interface (API), for use in Mobile and Web Application Projects </p>
              <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="https://langtranslate.herokuapp.com/" target="_blank">visit&RightArrow;</a></span>
              <span class="rounded-full bg-green-900 px-4 py-1 text-white uppercase">Completed</span>
            </div>
          </div>

        </div>

      </main>
</template>

<script>
export default {
    head(){
        return{
            'title':'iamdyt/Portfolio'
        }
    }
}
</script>