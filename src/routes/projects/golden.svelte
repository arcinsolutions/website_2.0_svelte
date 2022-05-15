<script>
	import ArrowDown from './../../assets/arrow_down.svelte';
	import GoldenLogo from '../../assets/golden_logo.png';
	import GoldenPlayer from '../../assets/GoldenPlayer.png';
</script>

<div class="bg-base-300">
	<section id="goldenHome">
		<div class="hero min-h-screen">
			<div class="hero-content flex-col lg:flex-row relative">
				<img
					src={GoldenLogo}
					class="max-w-sm rounded-lg shadow-2xl mask mask-squircle"
					alt="Golden"
				/>
				<div>
					<h1 class="text-5xl font-bold">Golden</h1>
					<p class="py-6">
						Play music in Discord without advertising, with good quality and all the important
						features that cost money at others.
					</p>
					<div class="text-center">
						<a href="#goldenFeatures" class="btn btn-primary">Features</a>
					</div>
				</div>
				<div class="-z-10 absolute -bottom-56 lg:block hidden">
					<ArrowDown />
				</div>
			</div>
		</div>
	</section>

	<section id="goldenFeatures">
		<div class="max-h-screen h-3/6 w-full flex justify-center p-10">
			<div class="card lg:card-side w-4/5 bg-base-200 shadow-2xl" id="projects">
				<div class="card-body">
					<h2 class="card-title text-2xl">GoldV</h2>
					<p class="text-xl">
						GoldV is a Hardcore RP Server for AltV with made with the <a
							href="https://athenaframework.com"
							class="link link-hover">Athena Framework</a
						> and complete Open Source like all of our Projects.
					</p>
					<div class="card-actions justify-end">
						<a href="projects/goldv" class="btn btn-outline">see More</a>
					</div>
				</div>
				<figure class="w-5/12 max-w-[41.666667%]">
					<img
						src={GoldenPlayer}
						alt="Golden Player"
						class="transition scale-100 transform-gpu skew-y-3 hover:transform-none"
						loading="lazy"
					/>
				</figure>
			</div>
		</div>
	</section>
</div>
