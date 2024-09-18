<script>
	import GateauFiche from "./GateauFiche.vue";

	export default {
		components: {
			GateauFiche,
		},
		data() {
			return {
				tarteList: [
					{
						image: "macarons.png",
						nomGateau: "La So Rhubarbe",
						description: "Le So Cheesecake Vanille",
					},
				],
			};
		},
	};
</script>

<template>
	<div>
		<h2>Tartes</h2>
		<div class="tartes list">
			<GateauFiche
				v-for="tarte in tarteList"
				:image="tarte.image"
				:nomGateau="tarte.nomGateau"
				:description="tarte.description" />
		</div>
	</div>
</template>
