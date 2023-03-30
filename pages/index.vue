<template>
  <div>
    <TopNav />
    <div style="opacity: 30%;">
      <BigImage image="https://img.freepik.com/free-photo/red-luxury-sedan-road_114579-5079.jpg?w=1380&t=st=1680202966~exp=1680203566~hmac=d7880e32b229730c5030ba718fd07a415608b76a510f0167c7e5f13f4cae51ec" />
    </div>
  </div>
</template>

<script>
import TopNav from '../components/nav/TopNav.vue'
import BigImage from '../components/gallery/BigImage.vue'
export default {
  name: 'IndexPage',
    components: { TopNav, BigImage }
}
</script>
