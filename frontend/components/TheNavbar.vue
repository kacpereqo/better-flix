<template>
  <nav id="navbar">
    <div class="logo">
      <img src="@/public/logo.png" />
      <h1>e-anima24</h1>
    </div>

    <div>
      <ul>
        <li>Home</li>
        <li>Anime</li>
        <li>Discord</li>
      </ul>
    </div>

    <div class="user">user</div>
  </nav>
</template>

<style scoped>
#navbar {
  height: var(--navbar-height);
  width: 100%;
  background-color: var(--second-color);
  font-size: var(--font-size-3);
  display: flex;
  padding: 0 1rem;
  justify-content: space-between;
  position: relative;
  align-items: center;
}

ul {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  display: flex;
  justify-content: center;
  align-items: center;
  list-style: none;
  gap: 2rem;
}

.logo {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  gap: 1rem;
}

.logo img {
  height: 100%;
}
</style>