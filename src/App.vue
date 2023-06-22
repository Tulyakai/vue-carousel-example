<template>
  <div>
    <h1>Vue 3 Carousel</h1>
    <h4>Tulyakai's example for Gamity eiei</h4>
    <Carousel :games="games" />
    <Carousel :games="games" />
    <Carousel :games="games" />
    <Carousel :games="games" />
    
  </div>
</template>

<script>
import Carousel from './components/CarouselComponent.vue'
export default {
  name: 'App',
  components: {
    Carousel,
  },
  data(){
    return{
      games: [
        {
          name: "Game 1",
          img: "https://picsum.photos/seed/1/300/500"
        },
        {
          name: "Game 2",
          img: "https://picsum.photos/seed/2/300/500"
        },
        {
          name: "Game 3",
          img: "https://picsum.photos/seed/3/300/500"
        },
        {
          name: "Game 4",
          img: "https://picsum.photos/seed/4/300/500"
        },
        {
          name: "Game 5",
          img: "https://picsum.photos/seed/5/300/500"
        },
        {
          name: "Game 6",
          img: "https://picsum.photos/seed/6/300/500"
        },
        {
          name: "Game 7",
          img: "https://picsum.photos/seed/7/300/500"
        },
        {
          name: "Game 8",
          img: "https://picsum.photos/seed/8/300/500"
        },
        {
          name: "Game 9",
          img: "https://picsum.photos/seed/9/300/500"
        },
        {
          name: "Game 10",
          img: "https://picsum.photos/seed/10/300/500"
        },
        {
          name: "Game 11",
          img: "https://picsum.photos/seed/11/300/500"
        },
        {
          name: "Game 12",
          img: "https://picsum.photos/seed/12/300/500"
        },
        {
          name: "Game 13",
          img: "https://picsum.photos/seed/13/300/500"
        },
        {
          name: "Game 14",
          img: "https://picsum.photos/seed/14/300/500"
        },
        {
          name: "Game 15",
          img: "https://picsum.photos/seed/15/300/500"
        }
    ]
    }
  }
}
</script>