<template>
  <div class="home">
    <Navbar />
    <h1>Home</h1>
    <FoodCard />
  </div>
</template>

<script>
// @ is an alias to /src
import Navbar from '@/components/Navbar.vue'
import FoodCard from '@/components/FoodCard.vue'

export default {
  name: 'PageHome',
        
        components: {
            Navbar, FoodCard
        }
    }
</script>
