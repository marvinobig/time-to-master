<template>
  <h1>Hello world. I'm Vue js</h1>
</template>

<style scoped>
h1 {
  animation-duration: 3s;
  animation-name: colourAnimate;
  animation-iteration-count: infinite;
}

@keyframes colourAnimate {
  from {
    color: red;
  }

  to {
    color: navy;
  }
}
</style>