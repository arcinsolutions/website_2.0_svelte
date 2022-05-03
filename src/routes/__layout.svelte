<script>
	import Footer from '../components/footer.svelte';
	import Nav from '../components/nav.svelte';
</script>

<div class="drawer">
	<input id="my-drawer-3" type="checkbox" class="drawer-toggle" />
	<div class="drawer-content flex flex-col">
		<Nav />

		<slot />

		<Footer />
	</div>
	<!-- Sidebar content -->
	<div class="drawer-side">
		<label for="my-drawer-3" class="drawer-overlay" />
		<ul class="menu p-4 overflow-y-auto w-80 bg-base-200">
			<li><a href="/">Home</a></li>
			<li><a href="/#about">About us</a></li>
			<div class="dropdown dropdown-hover">
				<h1 tabindex="0" class="btn btn-ghost normal-case">Projects</h1>
				<ul tabindex="0" class="dropdown-content menu p-2 shadow bg-base-300 rounded-box w-52">
					<li>
						<a href="/#projects">Overview</a>
					</li>
					<li>
						<a href="/projects/golden">Golden</a>
					</li>
					<li>
						<a href="/projects/goldv">GoldV</a>
					</li>
				</ul>
			</div>
			<li class="hover:bg-base-200 rounded-box">
				<a href="/#projects" class="z-10"
					>Projects
					<svg style="width:24px;height:24px" viewBox="0 0 24 24" class="fill-current -m-3">
						<path
							fill="currentColor"
							d="M7.41,8.58L12,13.17L16.59,8.58L18,10L12,16L6,10L7.41,8.58Z"
						/>
					</svg>
				</a>
				<ul class="bg-base-200 p-2 pt-8 -mt-6">
					<li>
						<a href="/projects/golden">Golden</a>
					</li>
					<li>
						<a href="/projects/goldv">GoldV</a>
					</li>
				</ul>
			</li>
		</ul>
	</div>
</div>

<style>
	@tailwind base;
	@tailwind components;
	@tailwind utilities;
</style>
