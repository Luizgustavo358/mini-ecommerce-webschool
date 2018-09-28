<template>
  <div>
    <h1>Hello World!</h1>
    <CcIntro></CcIntro>
  </div>
</template>

<script>
import CcIntro from './Intro'

export default {
  components: {
    CcIntro
  }
}
</script>

<style scoped>
  h1 {
    font-size: 50px;
    font-weight: bold;
  }
</style>
