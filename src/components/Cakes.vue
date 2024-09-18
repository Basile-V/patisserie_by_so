<script>
	import GateauFiche from "./GateauFiche.vue";

	export default {
		components: {
			GateauFiche,
		},
		data() {
			return {
				cakeList: [
					{
						image: "macarons.png",
						nomGateau: "Le Carrot Cake by SO",
						description: "Un classique gourmand à base de p",
					},
					{
						image: "macarons.png",
						nomGateau: "Le So Cheesecake Vanille",
						description: "Le So Cheesecake Vanille",
					},
					{
						image: "macarons.png",
						nomGateau: "Le So Myrtille",
						description: "Le So Cheesecake Vanille",
					},
					{
						image: "macarons.png",
						nomGateau: "Le Trois chocolats by So",
						description: "Le So Cheesecake Vanille",
					},
					{
						image: "macarons.png",
						nomGateau: "Le Cake Chocolat Glaçage Rocher Cacahuète by So",
						description: "Le So Cheesecake Vanille",
					},
				],
			};
		},
	};
</script>

<template>
	<h2>Cakes</h2>
	<div class="cakes list">
		<GateauFiche
			v-for="cake in cakeList"
			:image="cake.image"
			:nomGateau="cake.nomGateau"
			:description="cake.description" />
	</div>
</template>
