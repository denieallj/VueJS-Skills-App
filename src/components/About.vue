<template>
  <div class="about">
    <h1>This is an about page for {{name}}</h1>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna ali...</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: this.$route.params.name
    }
  }
}
</script>
