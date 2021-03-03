<template>
  <div>
    <Counter
      :year="2021"
      :month="2"
      :date="20"
      :hour="0"
      :minute="0"
      :second="0"
      :millisecond="0"
     />
  </div>
</template>

<script>
import Counter from '@/components/Counter'
  export default {
    components:{
      Counter
    }
  }
</script>

<style lang="scss" scoped>

</style>