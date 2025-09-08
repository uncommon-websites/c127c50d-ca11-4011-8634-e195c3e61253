<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Property feasibility, accelerated"
	subtitle="Advanced analysis for real estate development decisions."
	imageSrc="/generated/image-a-group-of-real-estate-developers-review.webp"
	centered={false}
/>
<!-- LogoScroller removed for stealth approach -->

<!-- Summary section removed for stealth approach -->

<Testimonials
	testimonials={[
		{
			name: "Sarah Martinez",
			position: "Development Director",
			company: "Pacific Coast Properties",
			quote:
				"Davis significantly accelerated our feasibility process. We can now move faster on opportunities.",
			image: "/generated/image-a-property-investment-meeting-room-fille.webp"
		}
	]}
/>

<Features
	title="Capabilities"
	subtitle="AI-powered property analysis"
	features={[
		{
			title: "Automated feasibility analysis",
			description: "Comprehensive property evaluation using advanced AI workflows.",
			image: "/generated/image-a-presentation-on-property-feasibility-a.webp"
		},
		{
			title: "Visual modeling",
			description: "Generate property renderings and development scenarios.",
			image: "/generated/image-a-california-property-development-site-d.webp"
		},
		{
			title: "Expert review",
			description: "Human-verified reports for accuracy and reliability.",
			image: "/generated/image-a-review-of-a-real-estate-feasibility-re.webp"
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Learn more"
	subtitle="Explore how Davis works."
	description="Discover our approach to property feasibility analysis."
	imageSrc="/generated/image-california-real-estate-development-proje.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Get in touch",
			variant: "primary"
		}
	]}
/>
