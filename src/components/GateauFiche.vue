<template>
	<div class="gateau-fiche">
		<img
			:src="`src/assets/images/${image}`"
			:alt="nomGateau"
			class="gateau-image" />
		<h3 class="gateau-nom">{{ nomGateau }}</h3>
		<p class="gateau-description">{{ description }}</p>
	</div>
</template>

<script>
	export default {
		name: "GateauFiche",
		props: {
			image: {
				type: String,
				required: true,
			},
			nomGateau: {
				type: String,
				required: true,
			},
			description: {
				type: String,
				required: true,
			},
		},
	};
</script>
