<script setup>
const props = defineProps({ title: String, center: Boolean });
</script>

<template>
  <section class="rounded-lg bg-gray-100 p-10 mt-10">
    <h2>{{ title }}</h2>
    <div class="flex">
      <div class="w-3/6" :class="{'grid place-content-center': center}">
        <slot name="left"></slot>
      </div>
      <div class="w-3/6">
        <slot></slot>
      </div>
    </div>
  </section>
</template>

<style scope>
h2 {
  font-weight: bolder;
}
</style>
