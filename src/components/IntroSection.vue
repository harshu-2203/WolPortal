<template>
    <header class="rounded-md flex flex-col-reverse my-16 mx-4  py-10 justify-between md:flex-row md:items-center">
      <div class="md:w-8/12">
        <div class="space-y-2">
          <div class="font-semibold text-xl text-wolgray md:text-3xl dark:text-neutral-200">
            <h1>Self taught</h1>
            <h1><a href="https://www.w3schools.com/whatis/whatis_frontenddev.asp?utm_source=wolmer.me" target="_blank"
                rel="noreferrer noopener"
                class="cursor-help border-b-2 font-poppin border-blue-700 text-blue-700 dark:border-neutral-500 dark:text-neutral-500">Frontend</a>
              web developer
              <br> and a Web3 enthusiast 
            </h1>
          </div>
          <p class="text-wolgray font-poppin">
            Hi there, My name is Karan Roy. I am a 
            self taught web developer based in India. I build complex web apps using frameworks like
            <a href="https://vuejs.org/?utm_source=wolmer.me" target="_blank" rel="noreferrer noopener"
              class="description-link linked-white">Vue.js</a>,
            <a href="https://reactjs.org/?utm_source=wolmer.me" target="_blank" rel="noreferrer noopener"
              class="description-link linked-white">React.js</a>
            and
            <a href="https://tailwindcss.com/?utm_source=wolmer.me" target="_blank" rel="noreferrer noopener"
              class="description-link linked-white">Tailwind CSS</a>.
          </p>
        </div>
        
        <LinkTab />
        
        
      </div>

      <div class="rounded-full mb-4 md:mb-0">
        <div smart-image="true" class="block rounded-full shadow-md shadow-wolgray mx-auto -mt-16 h-48 w-48 bg-cover bg-center select-none"
          style="background-image: url(./src/assets/cd/icon.png); background-position: center center; background-size: cover;">
          <!-- <img src="./src/assets/cd/icon.png" alt="image" loading="lazy" class="invisible">  -->
        </div>
      </div>
    </header>
    
  

</template>

<script setup>
import LinkTab from './LinkTab.vue';
</script>

<script>
export default{
    name: "IntroSection",
    
}
</script>
