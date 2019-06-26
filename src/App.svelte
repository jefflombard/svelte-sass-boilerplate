<script>
	export let name;
</script>

<style lang="scss" global>
	h1 {
		font-size: 100px;
		span {
			color: red;
		}
	}
</style>

<h1>Hello <span>{name}</span>!</h1>
