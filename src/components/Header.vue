<template>
  <div>
  <mu-appbar class="header" solt="default">
    {{CompanyName}}
  </mu-appbar>
  </div>
</template>

<script>
export default {
  CompanyName: '',
  data () {
    return {
      CompanyName: '西王集团智慧订餐系统'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.header{
  height:100px;
  text-align:center;
}
.title{
  font-size:20px;
}
</style>
