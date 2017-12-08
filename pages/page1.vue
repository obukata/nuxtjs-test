<template>
	<div>

	<Header />

		<div class="container">
			<div class="demo-headline">
				<h1 class="demo-logo">
					<div class="logo"></div>
					Page1
					<small>Study for Nuxt.js</small>
				</h1>
			</div>

			<h2 class="demo-panel-title">Title</h2>

			<div class="row demo-row">
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae aspernatur illo asperiores, quos, reiciendis facere unde omnis nesciunt quam distinctio dolores velit non deserunt totam. Nisi, sint accusamus nihil repellendus!</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae aspernatur illo asperiores, quos, reiciendis facere unde omnis nesciunt quam distinctio dolores velit non deserunt totam. Nisi, sint accusamus nihil repellendus!</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae aspernatur illo asperiores, quos, reiciendis facere unde omnis nesciunt quam distinctio dolores velit non deserunt totam. Nisi, sint accusamus nihil repellendus!</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae aspernatur illo asperiores, quos, reiciendis facere unde omnis nesciunt quam distinctio dolores velit non deserunt totam. Nisi, sint accusamus nihil repellendus!</p>
			</div>


			<h2 class="demo-panel-title">Title2</h2>

			<div class="row demo-row">
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae aspernatur illo asperiores, quos, reiciendis facere unde omnis nesciunt quam distinctio dolores velit non deserunt totam. Nisi, sint accusamus nihil repellendus!</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae aspernatur illo asperiores, quos, reiciendis facere unde omnis nesciunt quam distinctio dolores velit non deserunt totam. Nisi, sint accusamus nihil repellendus!</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae aspernatur illo asperiores, quos, reiciendis facere unde omnis nesciunt quam distinctio dolores velit non deserunt totam. Nisi, sint accusamus nihil repellendus!</p>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Beatae aspernatur illo asperiores, quos, reiciendis facere unde omnis nesciunt quam distinctio dolores velit non deserunt totam. Nisi, sint accusamus nihil repellendus!</p>
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