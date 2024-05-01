<script setup>
import SectionContainer from "./SectionContainer.vue";
</script>

<template>
  <div class="w-9/12 mx-auto">
    <SectionContainer title="How to do hover" :center="true">
      <template #left>
        <code> class="bg-orange-600 hover:bg-orange-200 </code>
      </template>
      <p class="p-10 bg-orange-600 hover:bg-orange-200">Do hover on me</p>
    </SectionContainer>
    <SectionContainer title="first, last, odd, and even" :center="true">
      <template #left>
        <pre> 
class="first:pt-0 last:pb-0 odd:bg-orange-800"
class="first:pt-0 last:pb-0 odd:bg-orange-800"
class="first:pt-0 last:pb-0 odd:bg-orange-800"
        </pre>
      </template>
      <ul class="border">
        <li class="my-2 first:mt-0 last:mb-0 odd:bg-orange-800 grid place-content-center text-white">texto 1</li>
        <li class="border-y border-black my-2 first:mt-0 last:mb-0 odd:bg-orange-800 grid place-content-center ">texto 2</li>
        <li class="my-2 first:mt-0 last:mb-0 odd:bg-orange-800 grid place-content-center text-white">texto 3</li>
      </ul>
    </SectionContainer>
  </div>
</template>
