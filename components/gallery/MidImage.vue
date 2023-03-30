<template>
    <div class="mid-image-container">
        <img :src="image"/>
    </div>
</template>
<script>
export default {
  name: 'MidImage',
  props: {
    image: {
        type: String,
        default: () => 'Pusty string'
    }
  }
}
</script>
<style scoped>
  .mid-image-container {
    display: flex !important;
    align-content: center;
    justify-items: center;
    margin-left: 10vw;
    width: 20%;
    height: 20%;
  }
</style>
