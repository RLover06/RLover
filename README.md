<html lang="en">
	<head>
		<meta charset="utf-8" />
		<link rel="icon" href="%sveltekit.assets%/favicon-blender.png" />
		<meta name="viewport" content="width=device-width, initial-scale=1" />
		<title>Over Regino • Portafolio</title>
		<!-- Google Fonts-->
		<link rel="preconnect" href="https://fonts.googleapis.com" />
		<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
		<link
			href="https://fonts.googleapis.com/css2?family=Caveat:wght@400;500&family=Roboto+Mono&family=Roboto:wght@400;900&family=Space+Grotesk:wght@500&display=swap"
			rel="stylesheet"
		/>
		%sveltekit.head%
	</head>

	<style>
		@import '/global.css';
		@import url('https://fonts.googleapis.com/css2?family=Caveat:wght@400;500&family=Roboto+Mono&family=Roboto:wght@400;900&family=Space+Grotesk:wght@500&display=swap');
	</style>

	<body
		data-sveltekit-preload-data="hover"
		class="custom-wrapper relative mx-auto max-w-7xl bg-slate-950 p-2 antialiased md:p-4"
	>
		<div style="display: contents">%sveltekit.body%</div>
	</body>
</html>

<style>
	html {
		scroll-behavior: smooth;
	}
</style>
