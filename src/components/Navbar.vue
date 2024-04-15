<script>
import Logo_Icon from '../assets/icons/Logo.vue'

export default {
  name: 'Navbar_Component',
  components: {
    LogoIcon: Logo_Icon
  }
}
</script>

<template>
  <div class="navbar_box">
    <LogoIcon />
    <ul>
      <li>Blogs</li>
      <li>Features</li>
      <li>Pricing</li>
      <li>Integration</li>
      <button>Start trial</button>
    </ul>
  </div>
</template>
