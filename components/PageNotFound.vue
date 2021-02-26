<template>
  <div>
    <h1>Page Not Found</h1>
    <img :src="require('@/assets/images/fe25.jpg')" alt="" />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
div {
  margin: 0 auto;
  display: flex;
  align-items: center;
  justify-content: center;
  width: 50rem;
}
h1 {
  font-size: 5rem;
}
img {
  width: 10rem;
  margin: 0 auto;
}
</style>
