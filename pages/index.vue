<template>
  <div>
    <!-- Display the "Hosted by Spidy" text -->
    <p class="text-center text-gray-500 mt-8">Hosted by Spidy</p>
  </div>
</template>

<script>
export default {
  layout: 'empty', // Use an empty layout to remove the default header/footer
};
</script>

<style scoped>
.text-center {
  text-align: center;
}

.text-gray-500 {
  color: #6b7280;
}

.mt-8 {
  margin-top: 2rem;
}
</style>
