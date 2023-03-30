<template>
    <div class="small-image-container">
        <img :src="image" class="small-image"/>
    </div>
</template>
<script>
export default {
  name: 'BigImage',
  props: {
    image: {
        type: String,
        default: () => 'Pusty string'
    }
  }
}
</script>
<style scoped>
  .small-image-container {
    display: flex;
    justify-content: center;
  }

  .small-image {
    align-content: center;
    justify-items: center;
    padding: 20px;
    width: 80%;
    height: 50%;
  }
</style>
