<script>
	import ArcinLogoSmall from '../assets/arcin_logo_small.svelte';
</script>

<nav>
	<div class="w-full navbar bg-gradient-to-b from-base-300 via-base-300/75 fixed z-50">
		<div class="flex-none lg:hidden">
			<label for="my-drawer-3" class="btn btn-ghost -mr-4">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					class="inline-block w-6 h-6 stroke-current"
				>
					<path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M4 6h16M4 12h16M4 18h16"
					/>
				</svg>
			</label>
		</div>
		<div class="flex-1 px-2 mx-2">
			<a href="/#home" class="btn btn-ghost">
				<ArcinLogoSmall />
			</a>
		</div>
		<div class="flex-none hidden lg:block">
			<ul class="menu menu-horizontal rounded-box p-2 pt-0">
				<!-- Navbar menu content here -->
				<li>
					<a href="/#home">Home</a>
				</li>
				<li>
					<a href="/#about">About us</a>
				</li>
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
</nav>
