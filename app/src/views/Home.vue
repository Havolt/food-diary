<template>
  <div class="home">
    <main class="content">
      <add-food></add-food>
    </main>
    
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
import AddFood from '@/components/AddFood.vue'

export default {
  name: 'home',
  components: {
    HelloWorld,
    AddFood
  }
}
</script>
