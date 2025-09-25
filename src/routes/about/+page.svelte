<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Precision",
			description: "Every stat, every score, every prediction powered by real-time data and proprietary algorithms that eliminate guesswork."
		},
		{
			title: "Community",
			description: "Fantasy sports are about connection—we build tools that bring leagues together and keep the competition alive year-round."
		},
		{
			title: "Innovation",
			description: "While competitors stick to outdated systems, we're redefining fantasy basketball with technology that actually works."
		}
	];
</script>

<SecondaryHero
	title="Solving world hunger"
	subtitle="one step at a time"
	imageSrc="https://www.unc.mn/image-placeholder.svg"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"It started during March Madness 2019. Our founder was managing a company fantasy league when a last-second buzzer-beater changed everything—except the manual scoring system couldn't keep up. Players were frustrated, arguments broke out over stat discrepancies, and half the league quit before the championship. That night, staring at spreadsheets until 2 AM, we realized millions of fantasy commissioners face this same nightmare: the tools that should bring people together were driving them apart.",
		"We knew fantasy sports could be better. While competitors focused on daily fantasy and big-money tournaments, we obsessed over the real problem—keeping traditional leagues alive and engaging. Our team built a proprietary player valuation algorithm that processes real-time game data instantly, eliminating manual scoring errors and providing insights that make every matchup thrilling. We started with college basketball because March Madness represents pure passion, the kind of energy that keeps fantasy leagues buzzing year-round.",
		"Today, we're transforming how 5 million fantasy players experience their favorite sport. Our platform doesn't just track stats—it predicts breakout performances, suggests strategic moves, and keeps leagues competitive from tip-off to championship. We're capturing a piece of the $1.2 billion fantasy sports market by solving the fundamental problem that drives commissioners crazy: turning administrative headaches into competitive advantages. This is just the beginning of making fantasy sports as thrilling as the games themselves."
	]}
/>

<!-- Our Culture Section -->
<Culture 
	{values} 
	title="What drives us." 
	subtitle="The principles behind every algorithm, every feature, and every game"
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to dominate your league?"
	subtitle="Start your fantasy season right"
	description="Stop losing players to manual scoring errors and boring interfaces. Give your company league the real-time stats and seamless experience that keeps everyone engaged from March Madness to championship night."
	imageSrc="/generated/image-a-professional-woman-at-her-desk-in-a-mo.webp"
/>
