<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
 <!-- <h1 class="text-3xl font-bold underline">Hello World!</h1> -->
<!-- <img src="myprofile.jpg" class="w-30 h-30 rounded-full" >

<p class="font-family Lucida Console, Courier New, monospace">Name: Amal</p>
<p>Description: I am a student from Politeknik Brunei</p> -->


<a href="#" class="flex flex-col items-center bg-white border border-gray-200 rounded-lg shadow md:flex-row md:max-w-xl hover:bg-gray-100 dark:border-gray-700 dark:bg-gray-800 dark:hover:bg-gray-700">
    <img class="object-cover w-full rounded-t-lg h-96 md:h-auto md:w-48 md:rounded-none md:rounded-l-lg" src="/myprofile.jpg" alt="">
    <div class="flex flex-col justify-between p-4 leading-normal">
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Amal Nabilah</h5>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 italic">A second year IT in Web Development student at Politeknik Brunei with an interest in develop app or website.</p>
    </div>
</a>


</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
