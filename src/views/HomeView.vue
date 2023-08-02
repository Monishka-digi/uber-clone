<template>
  <div ID="home" class="flex flex-col h-screen">
    <div class="m-3 mb-auto">
      <div class="grid grid-cols-2 gap-3 my-3">
        <ServiceSelectLarge 
          text="Ride"
          imageWidth="74"
          image="ride"
        />
        <ServiceSelectLarge 
          text="Food"
          imageWidth="72"
          image="food"
          :promo="true"
        /> 
      </div>
      <div class="grid grid-cols-2 gap-3 my-3">
        <ServiceSelectSmall 
          text="Ride"
          image="ride"
        />
      </div>
    </div>
  </div>
</template>

<script setup>
  import ServiceSelectSmall from '@/components/ServiceSelectSmall.vue';
  import ServiceSelectLarge from '@/components/ServiceSelectLarge.vue';
</script>
