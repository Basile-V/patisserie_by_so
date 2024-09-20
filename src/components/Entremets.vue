<script>
	import GateauFiche from "./GateauFiche.vue";

	export default {
		components: {
			GateauFiche,
		},
		data() {
			return {
				entremetList: [
					{
						image: "macarons.png",
						nomGateau: "Le Paris-Brest by So",
						description: "Un classique gourmand à base de p",
					},
				],
			};
		},
	};
</script>

<template>
	<div>
		<h2>Entremets</h2>
		<div class="entremets list">
			<GateauFiche
				v-for="entremet in entremetList"
				:key="entremet.nomGateau"
				:image="entremet.image"
				:nomGateau="entremet.nomGateau"
				:description="entremet.description" />
		</div>
	</div>
</template>
