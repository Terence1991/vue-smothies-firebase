<template>
  <div class="index container">
    <div class="card" v-for="smothie in smoothies" :key="smothie.id">
    
    
    </div>
  </div>
</template>




<script>
export default {
  name:  'index', 
  data () {
    return {
      smoothies: [
        {title: 'Ninja-Brew', slug: 'ninja-brew', ingrediants: ['bannas', 'coffe', 'milk'], id: '1'},
        {title: 'Magic-Mushroom', slug: 'magic-mushroom', ingrediants: ['mush'], id: '2'},
      ]
    }
  },
  methods: {
    deleteSmoothies(id) => {
      this.smoothies = this.smoothies.filter((smoothie) => {
        return smoothie.id != id;
      })
    }
    
  }

}
</script>