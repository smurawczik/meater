<script lang="ts">
	// Import necessary modules from Flowbite
	import { Card, Heading, ImagePlaceholder, P } from 'flowbite-svelte';

	// Define the profile data
	let profileType = {
		name: 'John Doe',
		occupation: 'Software Developer',
		bio: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed euismod justo nec mauris aliquam, vitae tincidunt nunc tincidunt.',
		email: 'john.doe@example.com',
		website: 'www.example.com'
	};

	export let profile: typeof profileType;
</script>

<Card class="border-2 border-sky-500 shadow-none">
	<ImagePlaceholder
		imgOnly
		src="https://via.placeholder.com/150"
		alt="Profile picture"
		class="mb-2 w-full"
	/>
	<Heading tag="h4" class="mb-1">{profile.name}</Heading>
	<P size="sm" class="mb-1">{profile.occupation}</P>
	<P>{profile.bio}</P>
	<a href={`mailto:${profile.email}`}>{profile.email}</a>
	<a href={profile.website}>{profile.website}</a>
</Card>
