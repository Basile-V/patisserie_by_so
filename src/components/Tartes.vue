<script>
	import GateauFiche from "./GateauFiche.vue";

	export default {
		components: {
			GateauFiche,
		},
	};
</script>

<template>
	<div>
		<h2>Tartes</h2>
		<div class="tartes list">
			<GateauFiche
				image="macarons.png"
				nomGateau="La So Rhubarbe<"
				description="Le So Cheesecake Vanille" />
		</div>
	</div>
</template>
