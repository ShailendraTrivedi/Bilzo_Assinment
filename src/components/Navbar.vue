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

<style scoped>
.navbar_box {
  box-sizing: border-box;
  margin: 0 auto;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  padding: 12px 120px;
  gap: 402px;
  width: 1366px;
  height: 68px;
  border-bottom: 1px solid #cbd5e1;
  flex: none;
  order: 0;
  flex-grow: 0;
}

.navbar_box>ul {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 0px;
  width: 411px;
  height: 44px;
  flex: none;
  order: 0;
  flex-grow: 0;
  list-style-type: none;
}

.navbar_box>ul>li {
  color: var(--500, #64748b);
  width: 131px;
  height: 44px;
  padding: 12px 20px 12px 20px;
  gap: 10px;
  opacity: 0px;
  cursor: pointer;
}
</style>