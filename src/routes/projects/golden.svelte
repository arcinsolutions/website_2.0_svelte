<script>
	import Divider from '/src/components/divider.svelte';
	import ArrowDown from '/src/assets/arrow_down.svelte';
	import GithubIcon from '/src/assets/github_icon.svelte';
	import DiscordIcon from '/src/assets/discord_icon.svelte';
</script>

<div class="bg-base-300">
	<section id="goldenHome">
		<div class="hero min-h-screen">
			<div class="hero-content flex-col lg:flex-row relative">
				<img
					src="https://cds.arcin.solutions/static/images/golden_logo.png"
					class="max-w-sm rounded-lg shadow-2xl mask mask-squircle"
					alt="Golden"
				/>
				<div>
					<h1 class="text-5xl font-bold">Golden</h1>
					<p class="py-6">
						Play music in Discord without advertising, with good quality and all the important
						features that cost money at others.
					</p>
					<p class="pb-6 underline">a new Version is currently in Development.</p>
					<div>
						<a
							href="https://github.com/arcinsolutions/Golden"
							target="blank"
							class="btn btn-primary mr-2"
						>
							<GithubIcon />
						</a>
						<a href="https://discord.gg/PX28nyVgdP" target="blank" class="btn btn-primary">
							<DiscordIcon />
						</a>
					</div>
				</div>
				<!-- <div class="-z-10 absolute -bottom-56 lg:block hidden">
					<ArrowDown />
				</div> -->
			</div>
		</div>
	</section>

	<!-- <section id="goldenFeatures">
		<div class="max-h-screen min-h-min w-full flex justify-center p-10">
			<div class="card lg:card-side w-4/5 bg-base-200 shadow-2xl" id="projects">
				<div class="card-body grid content-center">
					<div>
						<h2 class="card-title text-2xl">Music Player</h2>
						<p class="text-xl">
							See what is currently being played and use the Buttons to Control the Bot simple and easy.
						</p>
					</div>
					
				</div>
				<figure class="w-5/12 max-w-md lg:block self-center p-4">
					<img
						src="https://cds.arcin.solutions/static/images/golden_player.png"
						alt="Golden Player"
						class="transition scale-100 transform-gpu skew-y-3 hover:transform-none"
						loading="lazy"
					/>
				</figure>
			</div>
		</div>
		<Divider />
	</section> -->
</div>
