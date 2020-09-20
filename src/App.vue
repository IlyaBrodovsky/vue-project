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
      message: 'Menu'
    }
  }
}
</script>

<style>
#app {
  
}
</style>
