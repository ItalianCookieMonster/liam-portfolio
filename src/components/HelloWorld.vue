<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <h2>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Cupiditate, officia iure aliquam totam sequi reiciendis, iusto soluta laborum earum molestiae labore necessitatibus at error accusamus adipisci fugit illum, maxime obcaecati!</h2>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
