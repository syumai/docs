<template lang="pug">
.app.ui.raised.very.padded.text.container.segment
  h1 My Docs

  h2 Profile
  .ui.card
    .image
      img(src="res/icon.png")
    .content
      .header syumai
      .meta Web application developer
      .description
        i.icon.twitter
        a(href="https://twitter.com/__syumai", title="Twitter") @__syumai
      .description
        i.icon.github
        a(href="https://github.com/syumai", title="GitHub") @syumai

  h2 Links

  h3 2017.10.6 Gotanda.js

  p
    a(href="https://goo.gl/3qFbAc") Slide

  h4 Simple Counter Examples

  p
    a(href="https://syumai.github.io/react-vue-simple-counter/") Demo

  h5 Code

  p
    a(href="https://github.com/syumai/react-vue-simple-counter/tree/minimum") Minimum
  p
    a(href="https://github.com/syumai/react-vue-simple-counter/tree/with-loader") With loader

  h4 Vue on React Router

  p
    a(href="https://syumai.github.io/react-vue-examples/routers/react-router-vue/dist/index.html") Demo

  h5 Code

  p
    a(href="https://github.com/syumai/react-vue-examples/tree/master/routers/react-router-vue") Code

</template>

<script>
export default {
};
</script>

<style lang="sass" scoped>
.app.ui.segment
  margin-top: 36px
</style>

