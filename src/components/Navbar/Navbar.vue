<template>
  <div>
    <Nav class="background-white pt-5">
      <NavbarTitle class="t-center t-upper t-bold color-gray">Main</NavbarTitle>
    </Nav>
  </div>

</template>

<script>
import {Nav,NavbarTitle} from "@/components/Navbar/NavbarElements";

export default {
  name: "Navbar",
  components:
      {
        Nav,NavbarTitle
      }

}
</script>

