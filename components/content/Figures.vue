<template>
<div class="w-3/4 h-48 transition duration-300 ease-in-out hover:-translate-y-1 hover:scale-110 rounded md:flex bg-slate-100 rounded-xl p-8 md:p-0">
    <img class="w-24 h-24 md:w-48 md:h-auto md:rounded-none rounded-full mx-auto" :src="imagee" :alt="imagealt">
    <div class="pt-6 md:p-8 bg-gradient-to-r from-violet-500 to-fuchsia-500 text-center md:text-left space-y-4"> 
        <p class="text-lg text-purple-800 font-medium">"{{ quote }}"</p>  
      <div class="font-medium">
        <div class="text-sky-500">{{ person }}</div>
        <div class="text-cyan-700">{{ stuff }}</div>
    </div>
    </div>
</div>

</template>

 
<script>
export default {
  props: ['imagee', 'imagealt', 'quote', 'person', 'stuff']
}
</script>
