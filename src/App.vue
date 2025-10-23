<template>
  <div>
    <h1>🌿 Simple Vue Router Example</h1>
    <nav>
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </nav>

    <router-view />
  </div>
</template>

<style>
nav {
  margin: 20px 0;
}
a {
  text-decoration: none;
  margin: 0 10px;
  color: blue;
}
a.router-link-active {
  font-weight: bold;
  color: green;
}
</style>
