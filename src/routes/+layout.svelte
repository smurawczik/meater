<script>
	import '../app.css';
	import Footer from '../components/Layout/Footer.svelte';
	import Main from '../components/Layout/Main.svelte';
	import Navbar from '../components/Layout/Navbar.svelte';
</script>

<Main>
	<Navbar />
	<div class="max-h-full flex-grow overflow-y-auto px-4">
		<slot></slot>
	</div>
	<Footer />
</Main>

<style></style>
