<template>
  <div id="app">
    <div class="header">
      <div class="title">Demo Bank</div>
      <ul class="nav top-nav">
        <li>EN</li>
        <li>Support</li>
        <li>Profile</li>
        <li>Logout</li>
      </ul>
      <div class="btn close">✕</div>
    </div>
    <div class="main">
      <Navigation />
      <router-view class="content"></router-view>
    </div>
  </div>
</template>

<script>
import Navigation from '@/components/Navigation.vue'

export default {
  name: 'app',

  components: {
    Navigation
  }
}
</script>

<style lang="scss" src="@/styles/base.scss">
</style>
