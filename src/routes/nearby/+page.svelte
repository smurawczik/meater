<script>
	import ProfileCard from '../../components/ProfileCard/ProfileCard.svelte';

	let profiles = [
		{
			name: 'John Doe',
			occupation: 'Software Developer',
			bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
			email: '',
			website: '',
			age: 25
		},
		{
			name: 'Jane Doe',
			occupation: 'Software Developer',
			bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
			email: '',
			website: '',
			age: 25
		},
		{
			name: 'John Smith',
			occupation: 'Software Developer',
			bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
			email: '',
			website: '',
			age: 25
		},
		{
			name: 'John Doe',
			occupation: 'Software Developer',
			bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
			email: '',
			website: '',
			age: 25
		},
		{
			name: 'Jane Doe',
			occupation: 'Software Developer',
			bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
			email: '',
			website: '',
			age: 25
		},
		{
			name: 'John Smith',
			occupation: 'Software Developer',
			bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
			email: '',
			website: '',
			age: 25
		}
	];
</script>

<svelte:head>
	<title>Meater - nearby people</title>
</svelte:head>

<div class="grid grid-cols-3 gap-4">
	{#each profiles as profile}
		<ProfileCard {profile} />
	{/each}
</div>
