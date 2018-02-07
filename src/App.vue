<template>
	<div class="container">
		<navigation-menu></navigation-menu>
		<br/>
		<status-chips></status-chips>
		 <div class="chip">
			Jane Doe
		</div>
		<div class="chip">
			Outbound
		</div>
		<div class="chip">
			Origin: MA
		</div>
		<div class="chip">
			Destination: CA
		</div>
		<ul class="collapsible" data-collapsible="accordion">
			<qrq-address></qrq-address>
			<li>
				<div class="collapsible-header center"><i class="material-icons">toc</i> Line Items & Special Services</div>
				<div class="collapsible-body">
					<router-view></router-view>
				</div>
			</li>
		</ul>
	</div>
</template>

<script>
import NavigationMenu from './components/NavigationMenu.vue'
import QrqAddress from './components/QRQAddress.vue'

export default {
  name: 'app',
  components: {
	  NavigationMenu,
	  QrqAddress
  }
}
</script>
	
<style>
	.collapsible-body {
		padding: 1rem;
	}
</style>
