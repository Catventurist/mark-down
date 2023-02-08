<template>
    

<div class="grid grid-flow-col grid-rows-2 grid-cols-3 gap-8">
    <div class="hover:saturate-200 transform scale-110 rotate-6 translate-x-6 translate-y-40">
      <img :src="imga" alt="a" loading="lazy">
    </div>
    <div class="hover:grayscale col-start-3 transform scale-70 rotate-6 translate-x-2 translate-y-15">
      <img :src="imgb" alt="b" loading="lazy">
    </div>
    <div class="hover:translate-x-2 transform scale-150 translate-y-11">
      <img :src="imgc" alt="c" loading="lazy">
    </div>
    <div class="hover:invert transform translate-y-24">
      <img :src="imgd" alt="d" loading="lazy">
    </div>
    <div class="hover:sepia row-start-1 col-start-2 col-span-2 transform scale-120 translate-x-20 translate-y-4">
      <img class="rounded w-15" :src="imge" alt="e" loading="lazy">
    </div>
  </div>
</template>


<script>
export default {
  props: ['imga', 'imgb', 'imgc', 'imgd', 'imge']
}
</script>
