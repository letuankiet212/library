<template>
  <div id="app" >
    <div class=" flex j-start border-1 border-gray">
      <Navbar class="mr-2"></Navbar>

      <router-view/>
    </div>
  </div>
</template>

<style lang="scss">
</style>

<script>
import Navbar from "@/components/Navbar/Navbar";
export default {
  components: {Navbar}
}
</script>