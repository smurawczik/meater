<script>
	import { Navbar, NavBrand, NavHamburger, NavUl, NavLi } from 'flowbite-svelte';
</script>

<Navbar>
	<NavBrand href="/">
		<span class="self-center whitespace-nowrap text-xl font-semibold dark:text-white">Meater</span>
	</NavBrand>
	<NavHamburger />
	<NavUl>
		<NavLi href="/">Home</NavLi>
		<NavLi href="/profile">Profile</NavLi>
		<NavLi href="/nearby">Nearby</NavLi>
		<!-- <NavLi href="/pricing">Pricing</NavLi> -->
	</NavUl>
</Navbar>
