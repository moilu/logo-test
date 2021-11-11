<template>
    <nav>
      <button>logo</button>
      <button>
        <img src="@/assets/icons/gg_menu-left.svg" alt="">
      </button>
    </nav>
</template>

<script>

export default {
  name: "Header"
}
</script>

<style scoped>
nav {
  background-color: var(--main-bg-color);
  display: flex;
    align-content: center;
    justify-content: space-between;
  height: 56px;
  margin-bottom: 46px;
  padding: 20px;
  width: 100%;
}

button {
  background-color: var(--main-bg-color);
  border: none;
  color: var(--light-color);
  font-size: 18px;
  font-weight: 500;
  line-height: 27px;
  width: 40px;
}
</style>>
