<template>
  <header>
    <img alt="Vue logo" src="../assets/logo.png" height="50" />
    <h1>Vue.js</h1>
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/about">About</router-link></li>
      </ul>
    </nav>
  </header>
</template>
<style lang="scss">
header {
  display: flex;
  border-bottom: 1px solid #ccc;
  padding: 0.5rem 1rem;

  h1 {
    margin-left: 1rem;
    margin-top: 5px;
  }
}

nav {
  margin-left: auto;

  ul {
    list-style: none;
  }

  ul li {
    display: inline-flex;
    margin-left: 1rem;
  }
}
</style>
