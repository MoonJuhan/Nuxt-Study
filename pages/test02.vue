<template>
  <div class="container">
    <div>
      <Logo />
      <h1 class="title">
        This is Test02 Page
      </h1>
      <h3>{{ mountain }}</h3>
      <div class="links">
        <Nuxt-link to="/">Home</Nuxt-link>
      </div>
    </div>
  </div>
</template>

<script>
import axios from 'axios'

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
  async asyncData(context) {
    console.log('--- Async Data ---')
    console.log(context)
    let mountain = 'Mountain Name'

    const { data } = await axios.get('https://api.nuxtjs.dev/mountains')

    mountain = data[0].title

    return {
      mountain,
    }
  },
  middleware: 'test',
}
</script>

<style></style>
