<template>
	<nav id="nav">
		<div class="nav-wrapper">
			<ul class="right">
				<router-link tag="li" v-bind:to="'/ltl'" active-class="active">
					<a class="center"><i id="ltl" class="material-icons">local_shipping</i></a>
				</router-link>
				<router-link tag="li" v-bind:to="'/parcel'" active-class="active">
					<a class="center"><i id="parcel" class="material-icons">mail</i></a>
				</router-link>
				<router-link tag="li" v-bind:to="'/combined'" active-class="active">
					<a class="center"><i id="combined" class="tiny material-icons">local_shipping add mail</i></a>
				</router-link>
				<payment-types></payment-types>
			</ul>
		</div>
	</nav>
</template>

<script>
import PaymentTypes from './PaymentTypesDropdown.vue'

export default {
	name: 'NavigationMenu',
	data () {
		return {

		}
	},
	methods: {
	},
	props: [

	],
	components: {
		PaymentTypes
	}

}
</script>

<style lang="css" scoped>
	#combined {
		font-size: 20px;
	}
	nav li {
		width: 33.3%;
	}
	nav li:last-child {
		width: 33.4%;
	}
	ul {
		width: 100%;
	}
</style>
