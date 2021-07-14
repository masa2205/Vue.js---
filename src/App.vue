<template>
  <div id="app">
    <Helloworld title="validate" />
  </div>
</template>

<script>
  import Helloworld from './components/Helloworld'

  export default {
    name: 'app',
    components: {
      Helloworld
    },
    data: function() {
      return {
        message: 'validate',
        num:'1'
      };
    }
  }
</script>