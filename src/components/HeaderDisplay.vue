<template>
  <header class="header">
    <h2>Weather Application</h2>
    <p>{{ username }} 님 반갑습니다.</p>
  </header>
</template>

<script>
export default {};
</script>

<style>
.header {
  background-image: linear-gradient(to right, #ffecd2 0%, #fcb69f 100%);
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1em;
}
.header h2 {
  color: #fff;
}

.header p {
  font-size: 12px;
  color: #fff;
}
</style>
