<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Precision",
			description: "Every workflow automated, every stakeholder connected, every detail tracked—because successful projects start with flawless pre-construction coordination."
		},
		{
			title: "Partnership",
			description: "We integrate seamlessly with your existing systems and teams, building on what works while fixing what doesn't."
		},
		{
			title: "Performance",
			description: "Reducing project delays by 40% isn't just our promise—it's the measurable outcome of purpose-built pre-construction technology."
		}
	];
</script>

<SecondaryHero
	title="Where projects start right"
	subtitle="Built for those who build together"
	imageSrc="/generated/image-a-diverse-group-of-construction-professi.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"PreconOS started with a simple frustration shared by nearly every construction project manager we spoke to—winning a hard-fought bid, only to have pre-construction chaos eat into timelines and margins. Buried in spreadsheets, chasing subcontractor updates across disjointed email threads, and manually reconciling takeoffs, they were losing up to 40 hours a week—before a single brick was laid. It wasn't the jobsite causing delays and overruns. It was everything leading up to it.",
		"So we built PreconOS, a purpose-built platform for coordinating pre-construction with clarity and speed. Our integrated workflow automation connects estimators, architects, subcontractors, and stakeholders in real time—so information moves faster, decisions are clearer, and every bid has the structure to succeed. Designed to work with systems like Procore and P6, PreconOS fits into your existing stack without disruption. We started small, piloting with mid-size general contractors. But the impact was immediate—and measurable.",
		"Today, PreconOS supports over 10,000 active projects, helping ENR 400 contractors and growing firms reduce project delays by 40% and eliminate the communication gaps that drive up costs. Our mission is to bring order, efficiency, and reliability to the $1.8 trillion construction industry—starting where it matters most: pre-construction. Because getting it right up front means fewer surprises, less rework, and more profitable jobs for everyone down the line."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- CTA Section -->
<CallToAction
	title="Ready to build it right?"
	subtitle="Before you build it"
	description="Stop losing 40+ hours a week to manual takeoffs and fragmented communication. Join the ENR 400 general contractors already reducing project delays by 40% with PreconOS."
	imageSrc="/generated/image-a-professional-construction-project-mana.webp"
/>
