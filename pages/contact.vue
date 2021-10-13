<template>
  <main>
    <div>
      <p class="hello">Hello!</p>
      <h1>I'm Stuart Sewell.</h1>
    </div>
    <img src="~assets/images/profile.jpeg" alt="" />
  </main>
</template>

<script>
export default {}
</script>

<style scoped>
main {
  padding: 150px;
  display: flex;
  gap: 100px;
  background-color: var(--main-red);
}

.hello {
  margin: 0;
  padding: 0;
  padding-top: 40px;
  font-size: 40px;
  font-weight: 600;
  line-height: 20px;
}

h1 {
  display: inline-block;
  margin: 0;
  padding: 0;
  font-size: 90px;
  font-weight: 500;
  line-height: 115px;
  border-bottom: 3px solid #222222;
}

img {
  width: 500px;
  height: 500px;
  mask-image: url(~assets/images/splat.png);
  mask-size: contain;
  mask-repeat: no-repeat;
}
</style>
