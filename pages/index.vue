<template>
	<div>
		<Header />
		<h1>Hello world!</h1>
		<p>aa</p>
			<ul>
			<li><a href="/">index</a></li>
			<li><a href="/page1">page1</a></li>
			<li><a href="/page2">page2</a></li>
		</ul>
	</div>
</template>

<script>
import Header from '~/components/Header.vue'

export default {
	components: {
		Header
	}
}
</script>