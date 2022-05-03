<script>
	import About from '../components/about.svelte';
	import bg from '../assets/bg_home.jpg';
	import Projects from '../components/projects.svelte';
	import ArcinLogo from '../assets/arcin_logo.svelte';
</script>

<div class="bg-base-300">
	<section id="home" class="hero min-h-screen">
		<img
			src={bg}
			class="blur-sm brightness-50 object-cover h-screen min-w-full object-left"
			alt="Arcin Office"
		/>
		<div class="hero-content text-center relative min-h-screen w-screen overflow-hidden">
			<svg
				id="visual"
				viewBox="0 0 900 600"
				xmlns="http://www.w3.org/2000/svg"
				xmlns:xlink="http://www.w3.org/1999/xlink"
				version="1.1"
				class="-z-10 absolute fill-base-300 object-center object-fill min-h-screen"
			>
				<g transform="translate(425.83185487545876 287.2668386674961)">
					<path
						d="M98 -90.5C127.2 -68.8 151.1 -34.4 160.4 9.3C169.7 53 164.4 106.1 135.2 129.4C106.1 152.7 53 146.4 13.3 133.1C-26.5 119.9 -53 99.7 -74.9 76.4C-96.7 53 -113.9 26.5 -116 -2.2C-118.2 -30.9 -105.4 -61.8 -83.6 -83.4C-61.8 -105.1 -30.9 -117.5 1.8 -119.3C34.4 -121.1 68.8 -112.2 98 -90.5"
					/>
				</g>
			</svg>
			<div class="max-w-md">
				<div class="w-full content-center">
					<ArcinLogo />
				</div>
				<p class="pb-6">Free and Open Source projects for everyone.</p>
				<a href="#about" class="btn btn-primary">About us </a>
			</div>
		</div>
	</section>
	<section id="about">
		<About />
	</section>
	<div class="w-full flex justify-center">
		<div class="w-9/12 divider" />
	</div>
	<section id="projects">
		<Projects />
	</section>
</div>
