<template>
  <div class="home">
    <div>
      <img src='@/../public/svg/workout.svg'>
    </div>
    <div>
    <img src='@/../public/svg/food.svg'>
    </div>
    <div>
    <img src='@/../public/svg/heart.svg'>
    </div>
    <div>
    <img src='@/../public/svg/weight.svg'>
    </div>

    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'HomeView',
  components: {
    HelloWorld
  }
}
</script>

<style lang="scss">

.home {
  width: 100%;
  display: flex;
  flex-wrap: wrap;
  gap: 1em;

  > div {
    flex-grow: 1;
  }

  img { width: 33vw; }

}

</style>
