<template>
	<div class="hero">
		<header class="hero__header">
			<button class="searchBtn">Search for places</button>
			<button class="locationBtn">
				<i class="material-icons">my_location</i>
			</button>
		</header>

		<section class="weather__info">
			<div class="weather__icon">
				<img src="@/assets/Shower.png" alt="" />
			</div>

			<section class="current__temp">
				<p>
					<span class="temp__degrees">15</span>
					<span class="temp__icon">&deg;</span>
					<span class="temp__name">c</span>
				</p>
				<p class="weather__name">Shower</p>
			</section>
		</section>
		<div class="date">
			<span>Today</span>
			<span class="dot"></span>
			<span>Fri, 5 Jun</span>
		</div>
		<div class="current__location">
			<i class="material-icons">location_on</i>
			<span>Helsinki</span>
		</div>
		<div class="current__location">
			<i class="material-icons">location_on</i>
			<span>Helsinki</span>
		</div>
	</div>
</template>

<script>
export default {
	name: "AppHeader",
};
</script>

<style></style>
