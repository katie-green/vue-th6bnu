<template>
<div class="container text-center mt-5">

    <div class="container mb-5">
      <h2>Donate Here:</h2>

      <div class="p-2">Choose How Many: {{ picked }}</div>
      <div class="row">
      <div class="col">
      <input type="radio" id="one" value="One" v-model="picked" />
      <label for="one">One</label>
      </div>
      <div class="col">
      <input type="radio" id="two" value="Two" v-model="picked" />
      <label for="two">Two</label>
      </div>
      <div class="col">
      <input type="radio" id="three" value="Three" v-model="picked" />
      <label for="three">Three</label>
      </div>
      </div>
      </div>

</div>
<hr>
</template>

<script>
export default {
  name: 'Comp3',
  props: {
    msg: String
  },
    data() {
    return {
      picked: ''
    }
  }
}
</script>

<style scoped>
</style>