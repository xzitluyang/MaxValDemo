<template>
  <div>
    <mu-content-block style="height:150px;">放置滚动图片</mu-content-block>
    <mu-grid-list :cellHeight=80 :cols=3 :padding=10>
      <mu-grid-tile
      :subTitle="bottom"
      v-for="(item,index)
      in list" :key="index"
      :class={gridTile}
      >
        <img :src="item.image" />
        <span>{{item.title}}</span>
      </mu-grid-tile>
    </mu-grid-list>
  </div>
</template>

<script>
export default{
  data () {
    return {
      list: [
        {
          image: 'static/img/1.jpeg',
          title: 'test'
        }, {
          image: 'static/img/1.jpeg',
          title: 'test'
        }, {
          image: 'static/img/1.jpeg',
          title: 'test'
        }, {
          image: 'static/img/1.jpeg',
          title: 'test'
        }, {
          image: 'static/img/1.jpeg',
          title: 'test'
        }, {
          image: 'static/img/1.jpeg',
          title: 'test'
        }]
    }
  }
}
</script>

<style scoped>
.gridTile{
  margin:20px;
}
</style>
