<template>
  <div>
    <div>这里是博客导航</div>
    <nuxt/>
  </div>
</template>

<script>
export default {
  asyncData (context) {
    // called every time before loading the component
    return { 
      name: 'World'
    }
  },
  fetch () {
    // The fetch method is used to fill the store before rendering the page
  },
  head: {
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      { hid: 'description', name: 'description', content: '描述' }
    ],
    link: [
      { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css?family=Roboto' }
    ]
  }
}
</script>
