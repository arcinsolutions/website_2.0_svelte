<script>
	import MailIcon from '../assets/mail_icon.svelte';
	import aboutImg from '../assets/home_about.jpg';
	import GithubIcon from '../assets/github_icon.svelte';
	import BetteruptimeIcon from '../assets/betteruptime_icon.svelte';
	import FlarumLogo from '../assets/flarum_logo.svelte';
</script>

<h2 class="text-2xl font-bold xl:w-2/6 w-full text-center pt-4 -mb-4">About us</h2>
<div class="w-full flex justify-center p-10">
	<div class="card w-4/5 bg-base-200/50 shadow-2xl">
		<img
			src={aboutImg}
			alt="our Team"
			class="image-full h-72 object-cover object-center"
			loading="lazy"
		/>
		<div class="card-body">
			<h2 class="card-title font-normal -mt-3">why we do dis?</h2>
			<p>
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Ad magnam ut magni, maxime deleniti
				est sequi cum, explicabo quasi eveniet quod temporibus corrupti doloribus reiciendis
				architecto assumenda distinctio laboriosam natus?
			</p>
			<p>
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas beatae mollitia
				perspiciatis amet minima asperiores perferendis repellendus dignissimos sunt ut odio iure
				accusantium qui nemo dolorum hic, error officiis maiores!
			</p>
			<p>
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi laudantium repellat pariatur a
				quae sunt fuga maxime facere quidem obcaecati. Quidem nihil architecto odio voluptatibus
				fugiat laborum autem, perferendis ea.
			</p>
			<p class="divider" />
			<div class="card-actions justify-end max-h-min">
				<a class="btn btn-ghost" href="mailto:contact@arcin.solutions">
					<MailIcon />
				</a>
				<a href="https://github.com/arcinsolutions/" target="_blank" class="btn btn-ghost">
					<GithubIcon />
				</a>
				<a href="https://status.arcin.solutions" target="_blank" class="btn btn-ghost">
					<BetteruptimeIcon />
				</a>
				<a href="https://forum.arcin.solutions" target="_blank" class="btn btn-ghost">
					<FlarumLogo />
				</a>
			</div>
		</div>
	</div>
</div>
