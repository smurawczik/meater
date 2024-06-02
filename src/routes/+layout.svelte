<script>
	import '../app.css';
	import Footer from '../components/Layout/Footer.svelte';
	import Main from '../components/Layout/Main.svelte';
	import Navbar from '../components/Layout/Navbar.svelte';
</script>

<Main>
	<Navbar />
	<div class="flex-grow px-4">
		<slot></slot>
	</div>
	<Footer />
</Main>

<style></style>
