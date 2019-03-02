<template>
    <div>
        <home-header></home-header>
        <router-link to="/list">列表</router-link>
    </div>
</template>
<script>
import HomeHeader from './components/header'
export default {
  name: 'home',
  components: {
    HomeHeader
  }
}
</script>
