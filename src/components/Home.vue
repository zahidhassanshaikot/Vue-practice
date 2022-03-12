<template>
  <div>
    <h1>Home Component.. </h1>
    <User/>
    <Products/>
  </div>
</template>

<script>
import User from './User'
import Products from './products'
  export default {
    name: "Home",
    components: {
      User,
      Products,
    }
  }
</script>

<style scoped>
div{
  background-color: #a6d2fd;
  height: 500px;
}

</style>