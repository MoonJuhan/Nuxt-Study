<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        This is Test02 Page
      </h1>
      <div class="links">
        <Nuxt-link to="/">Home</Nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  layout: 'test',
  head() {
    return {
      title: 'Test02 Title',
      meta: [
        {
          name: 'author',
          content: 'Moon Juhan',
        },
      ],
    }
  },
}
</script>

<style></style>
