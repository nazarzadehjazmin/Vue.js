<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>{{ text }}</h2>
    <MyComponent></MyComponent>
  </div>
</template>


<script>
/*For adding another component to this file*/
import MyComponent from './MyComponent.vue';

export default {
  name: 'HelloWorld',
  components: {
    MyComponent
  },
  props: {
    msg: String
  },
  data() {
    return {
      text: "Hello world! I'm from components"
    }
  }
}
</script>


<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
