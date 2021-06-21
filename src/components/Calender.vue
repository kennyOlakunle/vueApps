<template>
  <div class="m-auto">
      <h1 class="text-2xl my-2 text-center">Vue Calender</h1>

      <section class="flex">
          <p class="w-10 h-10 text-center" v-for="day in days" :key="day">{{day}}</p>
      </section>

      <section class="flex">
          <p class="w-10 h-10 text-center" v-for="num in 3" :key="num">{{num}}</p>
      </section>
  </div>
</template>

<script>
export default {
    name: "Calender",

    data() {
        return {
            days: ["Sun", "Mon", "Tue", "Wed", "Thur", "Fri", "Sat"]
        }
    }

}
</script>

<style>

</style>