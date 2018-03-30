<template>
  <div id="app">
    <Header></Header>
    <Main></Main>
  </div>
</template>

<script>
import Header from './components/Header'
import Main from './components/Main'
export default {
  name: 'App',
  components: {
    Header,
    Main
  }

}
</script>

<style>
body{
  margin:0;
  padding:0;
}
</style>
