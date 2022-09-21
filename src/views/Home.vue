<template>
  <div class="home">
    <!-- 在这里使用自定义组件 -->
    <img alt="Vue logo" src="../assets/logo.png">
    <IButton size="large">你好</IButton>
  </div>
</template>

<script>
// @ is an alias to /src
import IButton from '@/components/IButton.vue'

export default {
  name: 'Home',
  components: {
    IButton
  }
}
</script>
