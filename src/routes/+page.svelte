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
	title="From weeks to hours. From guesswork to certainty."
	subtitle="Transform 4+ week property feasibility evaluations into 24-hour human-reviewed reports using agentic AI workflows and advanced diffusion models."
	imageSrc="/generated/image-a-group-of-real-estate-developers-review.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by leading real estate firms"
	logoUrls={[
		'https://logo.clearbit.com/blackstone.com',
		'https://logo.clearbit.com/brookfield.com',
		'https://logo.clearbit.com/prologis.com',
		'https://logo.clearbit.com/simon.com'
	]}
/>

<Summary
	title="What we do"
	text="Davis transforms property feasibility evaluations from 4+ week processes into 24-hour human-reviewed reports. We serve mid-sized real estate developers in California and international investment funds with agentic AI workflows and advanced diffusion models. Our platform eliminates the weeks of uncertainty that delay critical investment decisions, enabling faster market entry and more confident capital deployment at $10k–$20k per feasibility evaluation."
/>

<Testimonials
	testimonials={[
		{
			name: "Sarah Martinez",
			position: "Development Director",
			company: "Pacific Coast Properties",
			quote:
				"Davis reduced our feasibility timeline from 6 weeks to 24 hours. We closed on three prime California sites this quarter because we could move faster than competitors stuck in traditional evaluation cycles.",
			image: "/generated/image-a-property-investment-meeting-room-fille.webp"
		},
		{
			name: "James Chen",
			position: "Investment Principal",
			company: "Golden Gate Capital",
			quote:
				"The AI-powered analysis caught zoning issues that would have cost us $4.2M in delays. Davis's diffusion models showed us design possibilities we never considered, leading to 15% higher projected returns.",
			image: "/generated/image-a-modern-real-estate-development-team-me.webp"
		},
		{
			name: "Michael Torres",
			position: "Managing Partner",
			company: "Westbridge Development",
			quote:
				"We've scaled from 12 to 35 feasibility evaluations per quarter using Davis. The human-reviewed reports give us confidence to deploy capital faster while maintaining our rigorous due diligence standards.",
			image: "/generated/image-a-group-of-real-estate-investment-fund-e.webp"
		}
	]}
/>

<Features
	title="Core capabilities"
	subtitle="Advanced AI workflows that transform property feasibility evaluation"
	features={[
		{
			title: "Agentic AI workflow orchestration",
			description: "Deploy autonomous AI agents that coordinate complex feasibility analysis tasks. Our agentic systems handle zoning research, market analysis, and regulatory compliance checks simultaneously, reducing 4+ week timelines to 24 hours.",
			image: "/generated/image-a-presentation-on-property-feasibility-a.webp"
		},
		{
			title: "Advanced diffusion model visualization",
			description: "Generate photorealistic property renderings and design alternatives using cutting-edge diffusion models. Visualize development potential with unprecedented accuracy, enabling faster stakeholder alignment and investment decisions.",
			image: "/generated/image-a-california-property-development-site-d.webp"
		},
		{
			title: "California market intelligence",
			description: "Leverage deep California real estate data and regulatory expertise. Our specialized knowledge of local zoning, permitting, and market dynamics gives developers competitive advantages in the nation's most complex market.",
			image: "/generated/image-a-california-real-estate-development-pro.webp"
		},
		{
			title: "Human-reviewed quality assurance",
			description: "Every AI-generated report undergoes expert human review by seasoned real estate professionals. This hybrid approach ensures accuracy and reliability while maintaining the speed advantages of automated analysis.",
			image: "/generated/image-a-review-of-a-real-estate-feasibility-re.webp"
		},
		{
			title: "International fund integration",
			description: "Seamlessly serve global investment funds with standardized reporting formats and multi-currency analysis. Our platform scales from California-focused developers to international institutional investors.",
			image: "/generated/image-a-property-investment-meeting-room-fille.webp"
		},
		{
			title: "Rapid pilot deployment",
			description: "Start with low-risk pilot programs that run alongside existing processes. Prove ROI on 2-3 properties before scaling to full implementation, ensuring smooth adoption and immediate value demonstration.",
			image: "/generated/image-california-real-estate-development-proje.webp"
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Still waiting weeks for feasibility reports?"
	subtitle="See how Davis transforms your evaluation timeline."
	description="Let us show you how Davis reduces 4+ week feasibility evaluations to 24 hours with human-reviewed accuracy. Start with a pilot program on 2-3 properties to prove ROI before scaling to your full pipeline."
	imageSrc="/generated/image-california-real-estate-development-proje.webp"
	callsToAction={[
		{
			href: "/demo",
			label: "Book a demo",
			variant: "primary"
		},
		{
			href: "/pilot-program",
			label: "Start pilot program",
			variant: "secondary"
		}
	]}
/>
