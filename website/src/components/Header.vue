<template>
  <header class="header">
    <div class="container">
      <h1 class="logo">
        <router-link to="/">
          Saber
        </router-link>
      </h1>
      <ul class="menu">
        <li class="menu-item">
          <router-link to="/docs/">Guide</router-link>
        </li>
        <li class="menu-item">
          <a href="https://github.com/egoist/saber" target="_blank">GitHub</a>
        </li>
      </ul>
    </div>
  </header>
</template>

<style scoped>
.header {
  background: var(--theme-color);
  height: var(--header-height);
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
}

.header a {
  color: white;
}

.header >>> .container {
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.logo {
  font-size: 2rem;
  margin: 0;
  font-weight: 500;
}

.menu {
  list-style: none;
  margin-left: 0;
  font-size: 1rem;
  display: flex;
}

.menu-item {
  margin-left: 20px;
}
</style>
