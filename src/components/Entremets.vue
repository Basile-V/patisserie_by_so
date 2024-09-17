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
		<h2>Entremets</h2>
		<div class="entremets list">
			<GateauFiche
				image="macarons.png"
				nomGateau="Le Paris-Brest by So"
				description="Un classique gourmand à base de p" />
		</div>
	</div>
</template>
