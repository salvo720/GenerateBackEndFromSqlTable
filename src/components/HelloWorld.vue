<template>
	<div class="hello">
		<h1>{{ msg }}</h1>
		<p>
			For a guide and recipes on how to configure / customize this
			project,<br />
			check out the
		</p>

		<h3>Ecosystem</h3>
	</div>
</template>

<script setup lang="ts">
import { ref } from 'vue';

const msg = ref<boolean>(true);
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
	margin: 40px 0 0;
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
