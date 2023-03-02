<template>
  <div>
    <button @click="showAlert()">Submit 2</button>
  </div>
</template>
<script>
export default {
  props: {
    name: String,
  },
  methods: {
    showAlert() {
      alert(`Hello ${this.name}`);
    },
  },
};
</script>
