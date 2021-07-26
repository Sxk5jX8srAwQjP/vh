<template>
<div>
  <the-header></the-header>
  <the-main></the-main>
  <the-footer></the-footer>
  <!-- <footer></footer> -->
  <div class="light-box">light-box block</div>
</div>
</template>

<script>
import TheHeader from './components/TheHeader.vue'
import TheMain from './components/TheMain.vue'
import TheFooter from './components/TheFooter.vue'
export default {
  components: {
    TheHeader,
    TheMain,
    TheFooter
  }
}
</script>

<style>
*{
  box-sizing: border-box;
}
a, abbr, acronym, address, applet, article, aside, audio, b, big, blockquote, body, canvas, caption, center, cite, code, dd, del, details, dfn, div, dl, dt, em, embed, fieldset, figcaption, figure, footer, form, h1, h2, h3, h4, h5, h6, header, hgroup, html, i, iframe, img, ins, kbd, label, legend, li, mark, menu, nav, object, ol, output, p, pre, q, ruby, s, samp, section, small, span, strike, strong, sub, summary, sup, table, tbody, td, tfoot, th, thead, time, tr, tt, u, ul, var, video {
	margin: 0;
	padding: 0;
	border: 0;
	font-size: 100%;
	font: inherit;
	vertical-align: baseline;
}

body{
position: relative;
overflow-x: hidden;
background-color: red;
color: #707070;
font:16px Camphor, Open, Sans, Segoe Ui, sans-serif;
text-rendering: optimizeLegibility;
}

</style>
