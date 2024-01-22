<script setup lang="ts">
import MealBox from "../components/MealBox.vue";
import NavBar from "../components/NavBar.vue";
</script>

<template>
	<div class="h-screen flex-col relative">
		<div class="flex justify-center">
			<h1
				class="text-4xl font-bold text-orange-500 uppercase tracking-wide my-4"
			>
				Meritum
			</h1>
		</div>
		<h1 class="text-3xl font-bold text-slate-50 ml-4">Zamów</h1>
		<MealBox />
		<MealBox />
		<MealBox />
		<MealBox />
		<MealBox />
		<MealBox />
		<NavBar />
	</div>
</template>
