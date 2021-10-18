<template>
  <div id="my-component">
      <hr/>
    <h1>This is My Component</h1>
    <h2>{{ subtitle }}</h2>
    <hr/>
  </div>
</template>

<script>
export default{
    name: 'MyComponent',
    data() {
        return {
            subtitle: 'Subtitle from My Component'
        }
    }
};
</script>
