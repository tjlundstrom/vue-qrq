<template>
	<div class="row">
		<form class="col s12">
			<div class="input-field col s12">
				<input id="postal" class="validate" type="text">
				<label for="postal">{{ direction }} Postal Code</label>
			</div>
			<div class="input-field col s8">
				<input id="city" class="validate" type="text">
				<label for="city">{{ direction }} City</label>
			</div>
			<div class="input-field col s4">
				<input id="state" class="validate" type="text">
				<label for="state">{{ direction }} State</label>
			</div>
			<div class="input-field col s12">
				<input id="country" class="validate" type="text">
				<label for="country">{{ direction }} Country</label>
			</div>
		</form>
	</div>
</template>

<script>
export default {
  name: 'easy-address',
  data () {
		return {

		}
	},
	methods: {
	},
	props: [
		'direction'
	]
}
</script>

<style lang="css" scoped>

</style>
