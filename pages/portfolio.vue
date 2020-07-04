<template>
     <main>
        <!-- first section -->
        <div class=" lg:px-64 px-12 pt-12 lg:inline-flex mb-4">
          <div class="">
            <p class="text-xl lg:text-4xl text-blue-700 font-bold lg:font-medium uppercase">01.  meet me</p>
            <p class="text-justify lg:text-lg text-grey-darker">I am Lanre Olanlokun, a software developer based in Lagos, Nigeria. As a kid I have always wanted to be a Code Ninja. Growing up, I develop a penchant for software development & problem solving, and have written codes ranging from simple todos to complex applications.</p>
            <p class="text-justify lg:text-lg text-gray-darker"> As a computer science graduate, and a member of <span class='italic bg-white'>Programmers Den.</span> I have been part of others to build small and medium sized projects thereby building up my skills. </p>
          </div>

          <div class="w-full">
            <div class="bg-white border-t-8 rounded-lg border-blue-700 lg:ml-16">
              <img src="/svgs/author.jpg" class="object-contain mb-4" alt="">
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
          </div>
          </div>
          <!-- second project -->
          <div class="lg:w-1/2 ml-4 ">
            <div class=" bg-white shadow-lg w-full p-4 ">
              <img src="/svgs/Magazine.jpg" class="object-contain" alt="">
              <p class="lg:text-lg text-justify "> The Young Scholar Educational Magazine web portal. </p>
              <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="">visit&RightArrow;</a></span>
            </div>
          </div>
        </div>

        <div class="bg-gray-100  lg:px-64 px-12 pt-12 lg:inline-flex pb-1">
          <!-- third project -->
          <div class="lg:w-1/2 mb-4">  
          <div class=" bg-white shadow-lg w-full p-4 ">
            <img src="/svgs/Lassa Fever Expert System.jpg" class="object-contain" alt="">
            <p class="lg:text-lg text-justify "> An expert system for lassa fever, it features diagnosis, medication and advice.</p>
            <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="https://github.com/iamdyt/esgs">visit&RightArrow;</a></span>
          </div>
          </div>
          <!-- second project -->
          <div class="lg:w-1/2 ml-4 ">
            <div class=" bg-white shadow-lg w-full p-4 ">
              <img src="/svgs/SCMS.jpg" class="object-contain" alt="">
              <p class="lg:text-lg text-justify "> Student Complaint Management System, a platform for students of higher institutions to lodge relevant complaints to the appropriate departments. </p>
              <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="https://github.com/iamdyt/SCMS">visit&RightArrow;</a></span>
            </div>
          </div>

        </div>

        <!-- third row -->
        <div class="bg-gray-100  lg:px-64 px-12 pt-12 lg:inline-flex pb-1">
          <!-- third project -->
          <div class="lg:w-1/2 mb-4">  
          <div class=" bg-white shadow-lg w-full p-4 ">
            <img src="/svgs/coinconverter.jpg" class="object-contain" alt="">
            <p class="lg:text-lg text-justify "> A VueJs Powered App to convert digital currencies and tokens to NG FIAT.</p>
            <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="https://coinverta.herokuapp.com">visit&RightArrow;</a></span>
          </div>
          </div>
          <!-- second project -->
          <!-- <div class="lg:w-1/2 ml-4 ">
            <div class=" bg-white shadow-lg w-full p-4 ">
              <img src="svgs/SCMS.jpg" class="object-contain" alt="">
              <p class="lg:text-lg text-justify "> Student Complaint Management System, a platform for students of higher institutions to lodge relevant complaints to the appropriate departments. </p>
              <span class="rounded-full bg-gray-900 px-4 py-1 text-white uppercase"><a href="https://github.com/iamdyt/SCMS">visit&RightArrow;</a></span>
            </div>
          </div> -->

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