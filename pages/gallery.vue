<template>
    <div>
        <TopNav/>
        <div class="text">
          <h1 style="text-align: center;">Galeria</h1>
          <hr />
          <h2 style="padding: 20px;"> Wypożycz którąś z bestii (żart, niemiecka motoryzacja to awaryjny shit) </h2>
          <MidImage image="https://img.freepik.com/free-photo/red-luxury-sedan-road_114579-5079.jpg?w=1380&t=st=1680202966~exp=1680203566~hmac=d7880e32b229730c5030ba718fd07a415608b76a510f0167c7e5f13f4cae51ec" />
          <div style="display: flex; flex-direction: row; height: 200px; justify-content: center;">
            <SmallImage image="https://img.freepik.com/free-photo/red-luxury-sedan-road_114579-5079.jpg?w=1380&t=st=1680202966~exp=1680203566~hmac=d7880e32b229730c5030ba718fd07a415608b76a510f0167c7e5f13f4cae51ec" />
            <SmallImage image="https://img.freepik.com/free-photo/red-luxury-sedan-road_114579-5079.jpg?w=1380&t=st=1680202966~exp=1680203566~hmac=d7880e32b229730c5030ba718fd07a415608b76a510f0167c7e5f13f4cae51ec" />
            <SmallImage image="https://img.freepik.com/free-photo/red-luxury-sedan-road_114579-5079.jpg?w=1380&t=st=1680202966~exp=1680203566~hmac=d7880e32b229730c5030ba718fd07a415608b76a510f0167c7e5f13f4cae51ec" />
          </div>
          <button @click="showInfo">Pokaż więcej informacji</button>
        </div>
    </div>
</template>

<script>
import TopNav from '../components/nav/TopNav.vue'
import MidImage from '../components/gallery/MidImage.vue'
import SmallImage from '../components/gallery/SmallImage.vue'
export default {
  name: 'Gallery',
  components: { TopNav, MidImage, SmallImage },

  methods: {
    showInfo: () => {
        console.log('Witaj w konsoli')
        alert('Witaj')
    }
  }
}
</script>
<style scoped>
  .text {
    margin-inline: 50px;
    padding: 50px;
    border-style: dashed;
    border: 5px dashed yellow;
  }
</style>
