<script>
// import test from './assets/data.js'
import { test1, test2 } from './assets/data.js'

export default {
  name: 'App',
  data() {
    return {
      price1: 60,
      // 템플릿에서 쓰려면 인스턴스에 올려야 함
      test1,
      test2,
    }
  },
}
</script>

<template>
  <div class="bg-blue-100 h-screen text-center">
    <div>
      <h4>{{ price1 }} : 만원</h4>
      <p>{{ test1 }} : 만원</p>
      <h2>{{ test2 }} : 만원</h2>
    </div>
  </div>
</template>





<style scoped></style>
