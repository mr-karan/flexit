<template>
	<div id="app" class="container">
		<div class="row">
			<div class="one columns">
				<div class="box-column">
				<p>Columns</p>
				</div>
			</div>
			<div class="five columns">
				<div class="box-column">
				<p>Columns</p>
				</div>
			</div>
			<div class="six columns">
				<div class="box-column">
				<p>Columns</p>
				</div>
			</div>
		</div>
		<div class="row">
			<div class="four columns">
				<div class="box-column">
				<p>Columns</p>
				</div>
			</div>
			<div class="five columns">
				<div class="box-column">
				<p>Columns</p>
				</div>
			</div>
			<div class="three columns">
				<div class="box-column">
				<p>Columns</p>
				</div>
			</div>
		</div>
		<div class="row">
			<div class="columns">
				<div class="box-column">
				<p>Columns</p>
				</div>
			</div>
			<div class="one column">
				<div class="box-column">
				<p>Columns</p>
				</div>
			</div>
			<div class="one column">
				<div class="box-column">
				<p>Columns</p>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
export default {
	name: 'app',
	data () {
		return {
			msg: 'Welcome to Your Vue.js App'
		}
	}
}
</script>

<style lang="scss">
#app {
	font-family: 'Avenir', Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}

h1, h2 {
	font-weight: normal;
}

ul {
	list-style-type: none;
	padding: 0;
}

li {
	display: inline-block;
	margin: 0 10px;
}

a {
	color: #42b983;
}
</style>
