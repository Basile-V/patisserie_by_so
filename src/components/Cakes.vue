<script>
	import GateauFiche from "./GateauFiche.vue";

	export default {
		components: {
			GateauFiche,
		},
	};
</script>

<template>
	<h2>Cakes</h2>
	<div class="cakes list">
		<GateauFiche
			image="macarons.png"
			nomGateau="Le Carrot Cake by SO"
			description="Un classique gourmand à base de p" />
		<GateauFiche
			image="macarons.png"
			nomGateau="Le So Cheesecake Vanille"
			description="Le So Cheesecake Vanille" />
		<GateauFiche
			image="macarons.png"
			nomGateau="Le So Myrtille"
			description="Le So Cheesecake Vanille" />
		<GateauFiche
			image="macarons.png"
			nomGateau="Le Trois chocolats by So"
			description="Le So Cheesecake Vanille" />
		<GateauFiche
			image="macarons.png"
			nomGateau="Le Cake Chocolat Glaçage Rocher Cacahuète by So"
			description="Le So Cheesecake Vanille" />
		<GateauFiche
			image="macarons.png"
			nomGateau="Le Cake Chocolat Glaçage Rocher Cacahuète by So"
			description="Le So Cheesecake Vanille" />
	</div>
</template>
