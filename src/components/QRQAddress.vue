<template>
<li>
	<div class="collapsible-header center"> <i class="material-icons">directions</i> Address Information</div>
	<div class="collapsible-body">
		<div class="row">
			<div class="col s6">
				<easy-address direction="Origin"></easy-address>
			</div>
			<div class="col s6">
				<easy-address direction="Dest."></easy-address>
			</div>
		</div>
	</div>
</li>
</template>

<script>
import EasyAddress from './EasyShippingAddress.vue'

export default {
  name: 'qrq-address',
  components : {
	  EasyAddress
  }
}
</script>

<style scoped>

</style>
