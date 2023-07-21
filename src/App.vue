<template>
  <div class="wrapper">
    <Header />
    <main class="page">
      <Progres />
      <Protsessor />
      <Starts />
			<Proffesional /> 
			<Brends />
			<Study />
			<Avatars />
    </main>
		<Footer />
  </div>
</template>
<script >
import Header from './components/Header.vue' 
import Progres from "./components/Progres.vue"
import Protsessor from "./components/Protsessor.vue"
import Starts from "./components/Starts.vue"
import Proffesional from './components/Proffesional.vue'
import Brends from './components/Brends.vue'
import Study from "./components/Study.vue"
import Avatars from "./components/Avatars.vue"
import Footer from './components/Footer.vue'
export default {
  name: "App",
  components: {
    Header,
    Progres,
    Protsessor,
    Starts,
		Proffesional,
		Brends,
		Study,
		Avatars,
		Footer
  },
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
*,
*::after,
*::before {
	padding: 0;
	margin: 0;
	border: 0;
	box-sizing: border-box;
}
a {
	text-decoration: none;
}
ul,
ol,
li {
	list-style: none;
}
img {
	vertical-align: top;
}
h1,
h2,
h3,
h4,
h5,
h6 {
	font-weight: inherit;
	font-size: inherit;
}
html,
body {
	height: 100%;
	line-height: 150%;
	background: #FFF;
	font-size: 16px;
	font-weight: 400;
	color: #fff;
	font-family: 'Roboto', sans-serif;
	scroll-behavior: smooth;
}
/*--------------------------------------------------------------------------*/
.wrapper {
	min-height: 100%;
	overflow: hidden;
	display: flex;
	flex-direction: column;
}
._container {
  position: relative;
  z-index: 10;
	box-sizing: content-box;
	max-width: 1266px;
	margin: 0px auto;
	padding: 0 15px;
}
/* ----PAGE------------------ */
.page {
  background-image: url("./assets/imgs/main-img/main-bg-img.png");
  background-size: cover;
  background-position: center;
}
</style>
