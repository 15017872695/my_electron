<template>
  <div id="app">
	<MyHeader/>
	<router-view></router-view>
  </div>
</template>

<script>
  import MyHeader from "@/components/MyHeader.vue";
  export default {
    name: 'my_electron',
	
    components: {
      MyHeader,
    },
	
  }
</script>
<style lang="scss">
  /* CSS */
  #app,body,html{
    width: 100%;
    height: 100%;
    overflow: hidden;
	font-family: 'Source Sans Pro', sans-serif; 
  }
   * {
    margin: 0px;
    padding: 0px;
  }
  #app::-webkit-scrollbar{
    display: none;
  }
</style>
