<template>
  <div>
    <header class="header">
      <h2>Weather Application</h2>
      <p>{{ username }}님 반갑습니다!!</p>
    </header>
  </div>
</template>

<script>
export default {
  name: "weatherDisplay",
};
</script>

<style scoped>
.header {
  background: linear-gradient(90deg, #fc5c7d, #6a82fb);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1rem;
}
.header h2 {
  color: #fff;
}
.header p {
  font-size: 12px;
  color: #fff;
}
</style>
