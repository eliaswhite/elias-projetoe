<template>
  <header>
    <div class="menu-esquerdo">
      <span>Elias</span>
      <span>|</span>
      <span>Jogadores</span>
      <span>|</span>
      <span>Times</span>
    </div>
    <div class="menu-direito">
      <span>Sair</span>
    </div>
  </header>
  <RouterView />
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  height: 100vh;
  font-weight: normal;
}

header,
footer {
  height: 10%;
  background-color: rgb(44, 44, 143);
  color: white;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-left: 20px;
}

header span {
  padding: 0 20px;
}

main {
  height: 70%;
  background-color: rgb(180, 56, 238);
}
</style>
