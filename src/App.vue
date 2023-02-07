<template>
  <div class="main">
    <div style="flex: 1;overflow-y: scroll">
      <div v-for="i in arr" :key="i.name" style="">
        {{i.name}}
      </div>
    </div>
    <div class="input">
      <textarea style="width:100%"></textarea>
      <button>send</button>
    </div>
  </div>
</template>

<script>
//import Main from './components/Main.vue'

export default {
  name: 'App',
  components: {
    //Main
  },
  data() {
    return {
      arr: [{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},{name: 'ssdfsdfsdfsdf'},]
    }
  }
}
</script>


<style scoped>
.main {
  height: 705px;
  width: 100%;
  background-color: #9bbbd4;
  display: flex;
  flex-direction: column;
}
.input {
  width: 100%;
  height: 70px;
  display: flex;
}
</style>