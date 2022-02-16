<template>
<ul>
	<li
		v-for="letter in letters"
		:key="letter"
	>
		<button>
			{{ letter }}
		</button>
	</li>
</ul>
</template>

<script>
export default {
	name: 'Keyboard',

	data() {
		return {
			letters: ['Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
		}
	}
}
</script>

<style scoped>

</style>