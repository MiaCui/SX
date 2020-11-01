<template>
<p>
   <v-app>
    <v-content>
      <addItem></addItem>
    </v-content>
  </v-app>
</p>
</template>

<script>
import AddItem from './addItem'
export default {
  name: 'home',
  components: {
    AddItem
  }
}
</script>

<style scoped>

</style>
