<template>
  <div class="home">
    <!-- <img alt="Vue logo" src="../assets/logo.png"> -->
    <Elements/>
  </div>
</template>

<script>
// @ is an alias to /src
import Elements from '@/components/Elements.vue'

export default {
  name: 'home',
  components: {
    Elements
  }
}
</script>
