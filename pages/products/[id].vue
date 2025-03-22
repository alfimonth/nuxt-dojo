<script setup>
definePageMeta({
  layout: "products",
});

const { id } = useRoute().params;
</script>

<template>
  <div>
    <p>Product detail for {{ id }}</p>
    <p>
      Lorem ipsum dolor sit, amet consectetur adipisicing elit. Architecto ab
      tempora, adipisci maxime itaque error porro? Architecto quos deleniti
      voluptatibus, cumque velit officiis iure soluta expedita itaque facere
      molestias laboriosam.
    </p>
  </div>
</template>

<style scoped></style>
