<template>
  <layout />
    <section id="#">
      <div class="bg-sky-950 min-h-screen w-full flex items-center">
        <div class="container mx-auto px-12 py-16">
          <div class="flex flex-col md:flex-row items-center justify-between">
            <div class="md:w-1/2 text-white text-center md:text-left">
              <h1 class="text-6xl lg:text-8xl font-bold mb-4 text-yellow-400 cursor-pointer hover:scale-105 transition-transform drop-shadow-lg">Newbyte Solutions</h1>
              <p class="text-xl md:text-2xl mb-8">Elegant software design and IT services</p>
              <a href="#" class="bg-transparrent border-4 border-yellow-400 px-6 py-3 font-semibold text-xl text-white hover:bg-yellow-400 hover:text-white duration-300 transition-all">
                Get in touch
              </a>
            </div>
            <div class="md:w-1/2 mt-16 md:mt-0 flex justify-center">
              <svg viewBox="0 0 16 16" class="w-48 h-48 md:w-72 md:h-72 lg:w-96 lg:h-96" fill="none" xmlns="http://www.w3.org/2000/svg"><g id="SVGRepo_bgCarrier" stroke-width="0"></g><g id="SVGRepo_tracerCarrier" stroke-linecap="round" stroke-linejoin="round"></g><g id="SVGRepo_iconCarrier"> <path d="M2.34313 13.6569C1.78335 13.0971 1.32387 12.475 0.964684 11.8129C0.616724 12.3943 0.344087 12.943 0.180413 13.4311C0.0744537 13.7471 -0.0046342 14.0918 0.000211182 14.433C0.00512994 14.7793 0.101017 15.2121 0.444436 15.5556C0.787856 15.899 1.22074 15.9949 1.56705 15.9998C1.90818 16.0046 2.25291 15.9255 2.56888 15.8196C3.20464 15.6064 3.9433 15.2083 4.72317 14.6997C5.16617 14.4108 5.63715 14.0765 6.12819 13.7023C6.71718 13.8955 7.34639 14 8 14C11.3137 14 14 11.3137 14 8C14 7.34639 13.8955 6.71718 13.7023 6.12819C14.0765 5.63715 14.4108 5.16617 14.6997 4.72317C15.2083 3.9433 15.6064 3.20464 15.8196 2.56888C15.9255 2.25291 16.0046 1.90818 15.9998 1.56705C15.9949 1.22074 15.899 0.787856 15.5556 0.444436C15.2121 0.101017 14.7793 0.00512994 14.433 0.000211182C14.0918 -0.0046342 13.7471 0.0744537 13.4311 0.180413C12.943 0.344088 12.3943 0.616728 11.8129 0.964692C12.475 1.32388 13.0971 1.78336 13.6568 2.34314C13.3784 3.01413 13.0579 3.6038 12.6403 4.19604C12.6359 4.20221 12.6315 4.20838 12.6272 4.21457C11.7592 5.44256 10.5387 6.89539 9.07872 8.38692C8.8506 8.61996 8.62 8.85057 8.38695 9.07868C6.88789 10.546 5.42794 11.7714 4.19603 12.6402C3.60792 13.055 3.00258 13.3649 2.34313 13.6569Z" fill="#facc18"></path> <path d="M8 2C9.14392 2 10.2131 2.32012 11.1228 2.87567C10.2717 4.11121 8.95721 5.68369 7.32047 7.32043C5.6837 8.9572 4.11121 10.2717 2.87566 11.1227C2.32012 10.2131 2 9.14392 2 8C2 4.68629 4.68629 2 8 2Z" fill="#facc18"></path> </g></svg>
            </div>
          </div>
          <div class="hidden md:flex absolute bottom-0 left-0 right-0 items-center justify-center animate-bounce mb-4">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-24 w-24 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
              <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 14l-7 7m0 0l-7-7m7 7V3" />
            </svg>
          </div>
        </div>
      </div>
    </section>
    <section id="services">
      <div class="bg-white min-h-screen w-full flex items-center flex-col px-4">
        <h1 class="text-5xl md:text-7xl drop-shadow-lg font-bold tracking-wide text-yellow-400 my-16 text-center">Our services</h1>
        <div class="w-full flex justify-center items-center md:justify-evenly flex-col md:flex-row gap-8 md:gap-4">
          <div class="w-full md:w-1/5 min-h-96 bg-sky-950 text-white drop-shadow-lg flex space-y-6 items-center justify-center flex-col p-4">
            <h1 class="text-3xl md:text-4xl font-bold tracking-wider text-center">Web Development</h1>
            <p class="mx-4 text-center tracking-widest">We can build all types of websites for your needs, with the technologies you want.</p>
          </div>
          <div class="w-full md:w-1/5 min-h-96 bg-sky-950 text-white drop-shadow-lg flex space-y-6 items-center justify-center flex-col p-4">
            <h1 class="text-3xl md:text-4xl font-bold tracking-wider text-center">IKT</h1>
            <p class="mx-4 text-center tracking-widest">We can configure clients, servers, networks and software for you, based on your requirements.</p>
          </div>
          <div class="w-full md:w-1/5 min-h-96 bg-sky-950 text-white drop-shadow-lg flex space-y-6 items-center justify-center flex-col p-4">
            <h1 class="text-3xl md:text-4xl font-bold tracking-wider text-center">Other</h1>
            <p class="mx-4 text-center tracking-widest">We can provide technical expertise in many fields including stage production, media and much more.</p>
          </div>
        </div>
      </div>
    </section>
    <section id="team">
      <div class="w-full h-fit md:min-h-screen my-24 md:my-0 overflow-hidden relative">
        <div class="absolute bg-sky-950 h-[200vh] md:h-screen w-full -z-10 top-0 left-0 clip-path-custom"></div>
        <div class="w-full min-h-screen text-black flex flex-col justify-center items-center z-10">
          <h1 class="text-5xl md:text-7xl drop-shadow-lg font-bold tracking-wide text-yellow-400 mb-24">The Team</h1>
          <div class="w-full flex flex-col md:flex-row flex-wrap justify-center items-center gap-6 md:gap-10">
            <div class="bg-white backdrop-blur-sm p-6 rounded-lg flex flex-col items-center space-y-3 hover:scale-105 hover:shadow-[0_0_15px_rgba(250,204,24,0.7)] hover:border-yellow-400 border-2 border-transparent transition-all duration-300 w-64 shadow-lg">
              <img src="https://placehold.co/200x200" alt="Profile image of a team member" class="w-32 h-32 rounded-full object-cover shadow-lg">
              <h1 class="text-xl font-bold tracking-wide">Martinus</h1>
              <p class="text-center">IKT, Development, Stage</p>
              <p class="text-gray-800">martinus@newbyte.no</p>
            </div>
            <div class="bg-white backdrop-blur-sm p-6 rounded-lg flex flex-col items-center space-y-3 hover:scale-105 hover:shadow-[0_0_15px_rgba(250,204,24,0.7)] hover:border-yellow-400 border-2 border-transparent transition-all duration-300 w-64 shadow-lg">
              <img src="https://placehold.co/200x200" alt="Profile image of a team member" class="w-32 h-32 rounded-full object-cover shadow-lg">
              <h1 class="text-xl font-bold tracking-wide">Name</h1>
              <p class="text-center">Daily Operations</p>
              <p class="text-gray-800">example@newbyte.no</p>
            </div>
            <div class="bg-white backdrop-blur-sm p-6 rounded-lg flex flex-col items-center space-y-3 hover:scale-105 hover:shadow-[0_0_15px_rgba(250,204,24,0.7)] hover:border-yellow-400 border-2 border-transparent transition-all duration-300 w-64 shadow-lg">
              <img src="https://placehold.co/200x200" alt="Profile image of a team member" class="w-32 h-32 rounded-full object-cover shadow-lg">
              <h1 class="text-xl font-bold tracking-wide">Name</h1>
              <p class="text-center">Economy, Administration</p>
              <p class="text-gray-800">example@newbyte.no</p>
            </div>
            <div class="bg-white backdrop-blur-sm p-6 rounded-lg flex flex-col items-center space-y-3 hover:scale-105 hover:shadow-[0_0_15px_rgba(250,204,24,0.7)] hover:border-yellow-400 border-2 border-transparent transition-all duration-300 w-64 shadow-lg">
              <img src="https://placehold.co/200x200" alt="Profile image of a team member" class="w-32 h-32 rounded-full object-cover shadow-lg">
              <h1 class="text-xl font-bold tracking-wide">Name</h1>
              <p class="text-center">Stage</p>
              <p class="text-gray-800">example@newbyte.no</p>
            </div>
            <div class="bg-white backdrop-blur-sm p-6 rounded-lg flex flex-col items-center space-y-3 hover:scale-105 hover:shadow-[0_0_15px_rgba(250,204,24,0.7)] hover:border-yellow-400 border-2 border-transparent transition-all duration-300 w-64 shadow-lg">
              <img src="https://placehold.co/200x200" alt="Profile image of a team member" class="w-32 h-32 rounded-full object-cover shadow-lg">
              <h1 class="text-xl font-bold tracking-wide">Name</h1>
              <p class="text-center">IKT, Stage</p>
              <p class="text-gray-800">example@newbyte.no</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section id="contact">
      <div class="w-full min-h-100">
          <div class="w-full min-h-screen text-white flex flex-col justify-center items-center z-10">
            <h1 class="text-5xl md:text-7xl drop-shadow-lg font-bold tracking-wide text-yellow-400 mb-20">Contact us</h1>
            <div class="bg-sky-950 backdrop-blur-sm p-8 flex flex-col items-center space-y-6 hover:shadow-lg border-2 border-transparent transition-all duration-300 w-full max-w-2xl">
              <form class="w-full">
                <div class="flex flex-col space-y-2 mb-10">
                  <label for="name" class="text-lg font-semibold text-white">Name</label>
                  <input type="text" id="name" class="p-3 bg-white/90 focus:bg-white outline-none transition-all duration-300 focus:ring-2 focus:ring-yellow-400">
                </div>
                <div class="flex flex-col space-y-2 mb-10">
                  <label for="email" class="text-lg font-semibold text-white">Email</label>
                  <input type="email" id="email" class="p-3 bg-white/90 focus:bg-white outline-none transition-all duration-300 focus:ring-2 focus:ring-yellow-400">
                </div>
                <div class="flex flex-col space-y-2 mb-20">
                  <label for="message" class="text-lg font-semibold text-white">Message</label>
                  <textarea id="message" rows="5" class="p-3 bg-white/90 focus:bg-white outline-none transition-all duration-300 focus:ring-2 focus:ring-yellow-400"></textarea>
                </div>
                <div class="w-full flex justify-center">
                  <button type="submit" class="w-3/4 border-4 border-yellow-400 bg-transparent text-white py-4 font-semibold hover:bg-yellow-400 hover:scale-105 transition-all duration-300">Send Message</button>
                </div>
              </form>
            </div>
          </div>
        </div>
    </section>
</template>

<script>
  import layout from "./components/default.vue";

  export default {
    components: {
      layout
    }
  }
</script>