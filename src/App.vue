<template>

  <card :message='message'/>
</template>

<script>
import Card from '@/components/Card'

export default {
  name: 'App',
   components: {
    Card
  },
  data() {
    return {
        message: 'MENU',
        fontSize: 16,
        image: 'assets/apple.jpg',

    }
  }
}
</script>

<style>
#app {
  
}
</style>
