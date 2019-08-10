<template>
  <div>
    <h4>Hello, Vue!</h4>
    <p>Howdy from the Main component in this Vue application!</p>
  </div>
</template>

<script>
export default {
  mounted() {
    this.helloWorld();
  },
  data() {
    return {
      //
    };
  },
  methods: {
    helloWorld() {
      console.log("Vue up and running!");
    }
  }
};
</script>
