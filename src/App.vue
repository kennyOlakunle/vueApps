<template>
<AppHeader />
<div class="w-full flex">

 <Calender />

</div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import Calender from './components/Calender.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    Calender
  }
}
</script>

<style>
</style>
