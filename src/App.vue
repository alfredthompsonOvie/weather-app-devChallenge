<template>
	<!-- hero -->
	<app-hero />

	<section class="main section weather__details">
		<section class="weather__details--inner">
			<!-- select temp -->
			<div class="temp__type">
				<button class="celsiusBtn">&deg;c</button>
				<button class="fahrenheitBtn">&deg;f</button>
			</div>
			<!-- weekly highlights -->
			<div class="weekly__forecast">
				<div class="card--weekly-forecast">
					<p class="date--weekly-forecast">Tomorrow</p>
					<img src="@/assets/Sleet.png" alt="" class="icon" />
					<p class="temp">
						<span>16&deg;c</span>
						<span class="temp--alt">11&deg;c</span>
					</p>
				</div>
				<div class="card--weekly-forecast">
					<p class="date--weekly-forecast">Sun, 7 Jun</p>
					<img src="@/assets/Sleet.png" alt="" class="icon" />
					<p class="temp">
						<span>16&deg;c</span>
						<span class="temp--alt">11&deg;c</span>
					</p>
				</div>
				<div class="card--weekly-forecast">
					<p class="date--weekly-forecast">Mon, 8 Jun</p>
					<img src="@/assets/Thunderstorm.png" alt="" class="icon" />
					<p class="temp">
						<span>16&deg;c</span>
						<span class="temp--alt">11&deg;c</span>
					</p>
				</div>
				<div class="card--weekly-forecast">
					<p class="date--weekly-forecast">Tue, 9 Jun</p>
					<img src="@/assets/LightCloud.png" alt="" class="icon" />
					<p class="temp">
						<span>16&deg;c</span>
						<span class="temp--alt">11&deg;c</span>
					</p>
				</div>
				<div class="card--weekly-forecast">
					<p class="date--weekly-forecast">Wed, 10 Jun</p>
					<img src="@/assets/HeavyRain.png" alt="" class="icon" />
					<p class="temp">
						<span>16&deg;c</span>
						<span class="temp--alt">11&deg;c</span>
					</p>
				</div>
			</div>
			<!-- todays highlights -->
			<section class="todayHighlights">
				<h1 class="section__title">Today's HightLight</h1>
				<div class="today__details">
					<div class="card--todayHighlights">
						<h2>Wind Status</h2>
						
					</div>
				</div>
			</section>
		</section>
	</section>
</template>

<script>
// import AppHeader from "@/components/AppHeader.vue";
import AppHero from "@/components/AppHero.vue";
export default {
	components: {
		// AppHeader,
		AppHero,
	},
};
</script>

<style scoped>
header {
	line-height: 1.5;
}

.logo {
	display: block;
	margin: 0 auto 2rem;
}
</style>
