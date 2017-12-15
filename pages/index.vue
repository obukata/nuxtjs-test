<template>
	<div>

	<Header />

		<div class="container">
			<div class="demo-headline">
				<h1 class="demo-logo">
					<div class="logo"></div>
					OBU Nuxt
					<small>Study for Nuxt.js</small>
				</h1>
			</div>

			<h2 class="demo-panel-title">Buttons</h2>

			<div class="demo-row">
				<div class="col-xs-4">
					<a href="/" class="btn btn-block btn-lg btn-primary">Home</a>
				</div>
				<div class="col-xs-4">
					<a href="/page1" class="btn btn-block btn-lg btn-warning">Page1</a>
				</div>
				<div class="col-xs-4">
					<a href="/page2" class="btn btn-block btn-lg btn-default">Page2</a>
				</div>
			</div>

		</div>

		<Footer />

	</div>
</template>

<script>
import Header from '~/components/Header.vue'
import Footer from '~/components/Footer.vue'

export default {
	components: {
		Header,
		Footer
	}
}
</script>