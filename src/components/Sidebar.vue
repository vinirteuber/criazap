<template>
  <aside>
    <div class="perfil">
      <i class="fa-solid fa-user"></i>
    </div>
    <div class="status">
      <i class="fa-regular fa-pen-to-square"></i>
    </div>
    <div class="groups">
      <i class="fa-solid fa-users-between-lines"></i>
    </div>
    <div class="teme">
      <i class="fa-solid fa-moon"></i>
    </div>
    <div class="gear">
      <i class="fa-solid fa-gear"></i>
    </div>
  </aside>
</template>

<script>
export default {
  name: "SIDEBAR",
};
</script>

<style scoped>
aside {
  width: 400px;
  height: 100vh;
  background-color: aquamarine;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
}
i{
    font-size: 20pt;
    margin-top: 10px;
}
</style>
