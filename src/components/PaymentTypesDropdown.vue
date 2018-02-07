<template>
	<div>
		<a class="dropdown-button btn-floating btn-large halfway-fab waves-effect waves-light teal" href="#" data-activates="payment-types">
			<i class="material-icons">attach_money</i>
		</a>
		<ul id="payment-types" class="dropdown-content">
			<li><a href="#">Outbound</a></li>
			<li><a href="#">Inbound</a></li>
			<li><a href="#">Third Party</a></li>
		</ul>
	</div>	
</template>

<script>
export default {
  name: 'payment-types',
  data () {
		return {
			paymentTypes: [
				'Outbound',
				'Inbound',
				'Third Party'
			]
		}
	},
	methods: {
	},
	props: [
	]
}
</script>

<style scoped>

</style>
