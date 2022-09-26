<template>
  <div class="home">
    <!-- 在这里使用自定义组件 -->
    <img alt="Vue logo" src="../assets/logo.png">
    <AnchoredHeading :level="1">
      <a href="#hello-world">
        你好，我是定制标题标签大小的链接组件
      </a>
    </AnchoredHeading>
    <!-- 自定义的button按钮 -->
    <IButton size="large">你好，我是按钮组件</IButton>

    <!-- 自定义的标题组件 -->
    <heading :level="1">你好！！我是自己写的标题组件！！</heading>
  </div>
</template>

<script>
// @ is an alias to /src
import IButton from '@/components/IButton.vue'
import AnchoredHeading from '@/components/AnchoredHeading.vue'
import heading from '@/components/heading'

export default {
  name: 'Home',
  components: {
    IButton,
    AnchoredHeading,
    heading
  }
}
</script>
