<template>
  <header>
    <nuxt-link to="/" class="name">Stuart Sewell</nuxt-link>
    <nav>
      <nuxt-link to="/about">About</nuxt-link>
      <nuxt-link to="/blog">Blog</nuxt-link>
      <nuxt-link to="/contact">Contact</nuxt-link>
    </nav>
  </header>
</template>

<script>
export default {
  name: 'Nav',
}
</script>

<style>
nav a.nuxt-link-active {
  border-bottom: 3px solid #00331e;
  padding-bottom: 0px;
}

nav {
  position: relative;
  right: 0;
  display: flex;
  gap: 90px;
}

nav a {
  text-decoration: none;
  color: #00331e;
  font-weight: 400;
  font-size: 20px;
  margin-top: 6px;
  padding: 6px 6px 3px 6px;
}

header {
  padding: 28px 90px 28px 38px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: var(--main-red);
}

.name {
  font-family: 'Playfair Display', serif;
  text-decoration: none;
  font-weight: bold;
  font-size: 24px;
  color: #00331e;
}
</style>
