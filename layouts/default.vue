<template>
  <div class="bg">
		<header>
			<buttons/>
		</header>
    <nuxt />
  </div>
</template>
<script>
import Buttons from '~/components/Buttons.vue';

export default {
	components: {
		Buttons,
	},
};
</script>
<style>
header {
  position: fixed;
	top: 0;
	left: 0;
  z-index: 2;
	padding: 8px;
}

html {
  font-family: 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
    Roboto, 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

bg {
	background-color: #cfc;
}

.button--green {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #3b8070;
  color: #3b8070;
  text-decoration: none;
  padding: 10px 30px;
}

.button--green:hover {
  color: #fff;
  background-color: #3b8070;
}

.button--grey {
  display: inline-block;
  border-radius: 4px;
  border: 1px solid #35495e;
  color: #35495e;
  text-decoration: none;
  padding: 10px 30px;
  margin-left: 15px;
}

.button--grey:hover {
  color: #fff;
  background-color: #35495e;
}


.viewer {
	position: fixed;
	top: 0;
	right: 0;
	height: 100%;
	width: 100%;
}

html, body, .container, .viewer .container {
	height: 100%;
	width: 100%;
}
</style>
