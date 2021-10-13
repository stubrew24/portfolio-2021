<template>
  <section class="hero">
    <div>
      <h1>Hi, I am Stuart, Full Stack Developer</h1>
      <p>
        Amet minim mollit non deserunt ullamco est sit aliqua dolor do amet
        sint. Velit officia consequat duis enim velit mollit. Exercitation
        veniam consequat sunt nostrud amet.
      </p>
      <button class="cta">Download Resume</button>
    </div>
    <img src="~/assets/images/headshot.jpg" alt="" />
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
.hero {
  padding: 158px 148px;
  display: flex;
  gap: 100px;
}

p {
  margin-bottom: 40px;
}

img {
  width: 243px;
  height: 243px;
  border-radius: 50%;
  filter: drop-shadow(-5px 13px 0px #edf7fa);
}
</style>
