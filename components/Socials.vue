<template>
  <aside>
    <div class="links">
      <a href="https://www.twitter.com/stubrew24">
        <img src="~/assets/images/twitter.svg" alt="Twitter logo" />
      </a>
    </div>
  </aside>
</template>

<script>
export default {}
</script>

<style scoped>
aside {
  background-color: var(--main-red);
  display: flex;
  flex-direction: column;
  justify-content: end;
  padding-bottom: 38px;
}

.links {
  border-right: 12px solid #222222bf;
  display: flex;
  flex-direction: column;
  padding: 180px 38px 10px 38px;
  gap: 24px;
}
</style>
