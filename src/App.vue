<template>
  <div>
    <v-btn large>Normal</v-btn>
    <v-btn color="primary">Primary</v-btn>
    <router-view/>
  </div>
</template>

<script>
import { onMounted } from '@vue/composition-api'
export default {
  name: '',
  setup () {
    onMounted(() => {
      console.log(new Date().format('yyyy/MM/dd'))
    })
    return {

    }
  }
}
</script>

<style lang="scss" scoped>

</style>
