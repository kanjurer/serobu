<script>
	import Nav from './Nav.svelte'; 
</script>

<main>
	<Nav />
	<img id="cover-photo" src="landing-page-cover.jpg" alt="cover-photo" />
	<div id="homeform">
		<h1>Search Rentals Based on your Preference</h1>
		<input>
	</div>
</main>

<style>

#cover-photo{
	width:100%;
	filter:blur(2px);
}
#homeform{
	z-index: 1000;
	position: relative;
	color: black;
	top: -60vh;
	left:20vw;
}

</style>