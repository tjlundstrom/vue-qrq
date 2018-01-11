<template>
	<div id="nav" class="ui secondary pointing three item menu">	
		<router-link class="item" v-bind:to="'/ltl'" active-class="active"><i class="shipping icon"></i></router-link>
		<router-link class="item" v-bind:to="'/parcel'" active-class="active"><i class="open envelope icon"></i></router-link>
		<router-link class="item" v-bind:to="'/combined'" active-class="active">
			<i class="shipping icon"></i>
			<i class="plus icon"></i>
			<i class="open envelope icon"></i>
		</router-link>
	</div>
</template>

<script>
export default {
	name: 'NavigationMenu',
	data(){
		return{}
	},
	methods: {
	}

}
</script>

<style lang="css" scoped>
	#nav {
		width: 20%;
		margin-left: 40% !important;
	}
	i.icon {
		color: #2c3e50;
	}
</style>
