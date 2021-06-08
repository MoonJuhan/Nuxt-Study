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

<style>
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.title {
  font-family: 'Quicksand', 'Source Sans Pro', -apple-system, BlinkMacSystemFont,
    'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>
