<template>
  <div class="login-card">
    <header class="login-header">
      <h1 id="page-title">Thanks for your particpation!</h1>
    </header>
    </div>
</template>

<script>
export default {
methods: {
    previous() {
      this.$emit("previous");
    },
}
}
</script>

<style scoped>
.login-card {
  background: #fff;
  margin: 0 auto;
  padding: 0 20px;
  height: 150px;
  border-top: 0;
  text-align: center;
  
  border-radius: 1rem;
  box-shadow: 0 16px 24px 0 rgb(0 0 0 / 8%);
  max-width: 450px;
}
.login-header {
  margin-bottom: 20px;
  display: flex;
  flex-direction: column;
}
</style>