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
	title="Build smarter. Start earlier."
	subtitle="Streamline pre-construction workflows and cut delays."
	imageSrc="/generated/image-a-group-of-construction-project-managers.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/procore.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/turner.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/skanska.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/gilbane.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="PreconOS connects all stakeholders on a single platform to streamline pre-construction workflows for general contractors managing large commercial projects. We eliminate the 40+ hours per week wasted on manual takeoffs and fragmented communication that cause costly delays. Our integrated workflow automation reduces project delays by 40% while helping contractors win more profitable bids through faster, more accurate pre-construction coordination."
/>

<Testimonials
	testimonials={[
		{
			name: "Miguel Rodriguez",
			position: "VP of Preconstruction",
			company: "Meridian Construction",
			quote:
				"PreconOS cut our takeoff time from 8 hours to 2 hours per project. We're winning 30% more bids because we can respond faster and more accurately than our competitors.",
			image: "/generated/image-a-professional-headshot-of-miguel-rodrig.webp"
		},
		{
			name: "Jennifer Chen",
			position: "Project Director",
			company: "Summit Builders",
			quote:
				"We eliminated $2.3M in change orders last quarter alone. The integrated communication eliminated the gaps that used to cost us big on material delays and rework.",
			image: "/generated/image-a-professional-headshot-of-jennifer-chen.webp"
		},
		{
			name: "David Thompson",
			position: "Construction Executive",
			company: "Atlas Development",
			quote:
				"Our project timelines improved by 6 weeks on average. The automated workflows connect our entire team from architects to subcontractors in real-time.",
			image: "/generated/image-a-professional-headshot-of-david-thompso.webp"
		}
	]}
/>

<Features
	title="Core capabilities"
	subtitle="Streamline pre-construction workflows that determine project success"
	features={[
		{
			title: "Automated takeoff intelligence",
			description: "Transform 40+ hours of manual takeoffs into minutes with AI-powered quantity extraction. Win more profitable bids through faster, more accurate estimating.",
			image: "/generated/image-a-construction-team-gathered-around-a-la.webp"
		},
		{
			title: "Unified stakeholder communication",
			description: "Connect all subcontractors, suppliers, and team members on a single platform. Eliminate fragmented communication that causes costly delays and misaligned expectations.",
			image: "/generated/image-a-busy-construction-site-with-workers-ac.webp"
		},
		{
			title: "Predictive project risk analysis",
			description: "Identify potential delays and cost overruns before they impact your timeline. Our analytics reduce project delays by 40% through proactive risk management.",
			image: "/generated/image-a-group-of-construction-workers-on-site-.webp"
		},
		{
			title: "Seamless legacy integration",
			description: "Work within your existing Procore and P6 workflows without disruption. Phased implementation ensures smooth adoption while preserving established processes.",
			image: "/generated/image-a-team-of-architects-and-engineers-in-an.webp"
		},
		{
			title: "Real-time collaboration workspace",
			description: "Enable instant updates and decision-making across all project stakeholders. Reduce coordination time while maintaining complete project visibility and control.",
			image: "/generated/image-builders-and-architects-at-a-constructio.webp"
		},
		{
			title: "Intelligent bid optimization",
			description: "Leverage historical data and market insights to optimize bid strategies. Increase win rates on profitable projects through data-driven pre-construction planning.",
			image: "/generated/image-construction-bid-documents-with-optimiza.webp"
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Still stuck in manual workflows?"
	subtitle="See how much time your team could be saving."
	description="Let us show you how PreconOS reduces delays, frees up your estimators, and helps win more bids—all without disrupting your current tools. Start with a pilot program that runs alongside your existing Procore and P6 workflows."
	imageSrc="/generated/image-a-cheerful-construction-project-manager-.webp"
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
