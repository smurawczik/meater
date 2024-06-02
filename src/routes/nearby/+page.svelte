<script>
	import ProfileCard from '../../components/ProfileCard/ProfileCard.svelte';

	let profiles = [
		{
			name: 'John Doe',
			occupation: 'Software Developer',
			bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
			email: '',
			website: ''
		},
		{
			name: 'Jane Doe',
			occupation: 'Software Developer',
			bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
			email: '',
			website: ''
		},
		{
			name: 'John Smith',
			occupation: 'Software Developer',
			bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
			email: '',
			website: ''
		}
	];
</script>

<svelte:head>
	<title>Meater - nearby people</title>
</svelte:head>

<h2>Nearby</h2>

<div class="grid grid-cols-3 gap-4">
	{#each profiles as profile}
		<ProfileCard {profile} />
	{/each}
</div>
