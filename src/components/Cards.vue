<template>
    <div>
    <Cards class="card" style="width: 18rem;">
      <img v-bind:src="card.imgSrc" class="card-img-top" alt="..." />
      <div class="card-body">
        <h5 class="card-title">{{card.name}}</h5>
        <p class="card-text">{{card.description}}</p>
      </div>
    </Cards>
  </div>
</template>

<script>
export default {
    name: 'Cards',
    props:['card']
}
</script>
<!--Keegan Whitener-->
<!--This page was suppose to put out the movie cards, but I couldn't seem to find out what it meant by imgSrc not definded even though the infomation was added into the code via mounted even before the Cards.vue even ran.-->