<template>
  <section>
    <div>
      <hr />
      <p class="hello">Hello!</p>
      <h1>I'm Stuart Sewell.</h1>
      <p class="blurb">
        A full stack developer primarily focused on the JavaScript stack
        including React, Node.js and TypeScript. Also experienced in PHP, MySQL
        and Ruby. Always keen to learn new languages and approaches to solving
        problems.
      </p>
    </div>
    <img
      src="~assets/images/profile.jpeg"
      alt="Stuart Sewell headshot"
      width="500"
      height="500"
    />
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
section {
  padding: 60px 90px;
  display: flex;
  justify-content: space-between;
  gap: 100px;
  background-color: var(--main-red);
  width: 100%;
}

.hello {
  margin: 0;
  margin-left: 70px;
  padding: 0;
  padding-top: 40px;
  font-size: 40px;
  font-weight: 600;
  line-height: 20px;
}

.blurb {
  margin: 15px 0 0 70px;
  padding: 0;
  font-size: 27px;
  font-weight: 400;
}

h1 {
  display: inline-block;
  margin: 0;
  margin-left: 70px;
  padding: 0;
  font-size: 90px;
  font-weight: 500;
  line-height: 115px;
  border-bottom: 3px solid #222222;
}

hr {
  border: none;
  border-bottom: 12px solid #222222bf;
  display: inline-block;
  width: 168px;
  margin-bottom: 50px;
}

img {
  width: 500px;
  height: 500px;
  mask-image: url(~assets/images/splat.png);
  mask-size: contain;
  mask-repeat: no-repeat;
}
</style>
