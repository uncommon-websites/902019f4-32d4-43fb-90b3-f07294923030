<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";

	// Icons
	import IconNetwork from "~icons/lucide/network";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconShieldCheck from "~icons/lucide/shield-check";
	import IconTarget from "~icons/lucide/target";
	import IconKey from "~icons/lucide/key";
	import IconUsers from "~icons/lucide/users";
</script>

<CenteredTextOnlyHero
	title="Capital for outliers who define categories"
	subtitle="Strategic investment for elite founders building the next generation of iconic companies through verified networks and mystique-driven deal flow."
	imageSrc="/generated/image-a-candid-photograph-of-two-experienced-p.webp"
	callsToAction={[
		{ href: "/contact", label: "Explore partnership" },
		{ href: "/portfolio", label: "View portfolio" }
	]}
/>
<LogoScroller
	label="Backing category-defining companies"
	logoUrls={[
		'https://cdn.brandfetch.io/stripe.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/notion.so/w/400/h/400/logo',
		'https://cdn.brandfetch.io/figma.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/coinbase.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="Who we back"
	text="We invest in elite founders building category-defining companies that reshape entire industries. Through our verified network of portfolio companies and shadow capital approach, we provide strategic investment beyond the commoditized relationships of traditional venture capital. Our mystique-driven deal flow connects us with the outliers who define the next generation of iconic businesses."
/>

<Testimonials
	testimonials={[
		{
			name: "Mei Chen",
			position: "Founder & CEO",
			company: "Quantum Dynamics",
			quote:
				"Their strategic capital accelerated our Series B close by four months, saving us from dilutive bridge financing. The shadow network intro to our lead investor was worth the entire partnership.",
			image: "/generated/image-a-confident-asian-woman-founder-age-40s-.webp"
		},
		{
			name: "Marcus Williams",
			position: "Co-founder",
			company: "Apex Infrastructure",
			quote:
				"Working with Shadow Capital cut our fundraising risk entirely. Their verified portfolio introductions opened doors that took competitors years to access. We closed oversubscribed in six weeks.",
			image: "/generated/image-a-black-male-founder-in-his-40s-dressed-.webp"
		},
		{
			name: "Layla Nazari",
			position: "Founder",
			company: "Cipher Security",
			quote:
				"The mystique-driven approach eliminated traditional due diligence friction, saving us three months and $200K in legal costs. Their strategic guidance was worth multiples of the capital deployed.",
			image: "/generated/image-a-middle-eastern-woman-entrepreneur-mid-.webp"
		}
	]}
/>

<Features
	title="Built for outlier founders"
	subtitle="Strategic advantages that transcend traditional venture capital"
	features={[
		{
			title: "Shadow network access",
			description:
				"Private deal flow through verified founder networks that surface opportunities before they reach traditional channels. Elite founders introduce elite founders.",
			icon: IconNetwork
		},
		{
			title: "Strategic capital",
			description:
				"Investment partnerships that provide category-defining expertise alongside capital. We've built unicorns, not just funded them.",
			icon: IconTrendingUp
		},
		{
			title: "Stealth-backed portfolio",
			description:
				"Proven track record with successful unicorns who value discretion over publicity. Our results speak through founder references, not press releases.",
			icon: IconShieldCheck
		},
		{
			title: "Outlier founder focus",
			description:
				"Purpose-built for elite founders creating new categories, not iterating on existing markets. We invest in vision, not validation.",
			icon: IconTarget
		},
		{
			title: "Mystique-driven selection",
			description:
				"Exclusive partnerships based on strategic fit and long-term potential. We choose quality relationships over transactional volume.",
			icon: IconKey
		},
		{
			title: "Verified introductions",
			description:
				"Trust established through portfolio company referrals and shared network connections. Anonymity concerns resolved through proven relationships.",
			icon: IconUsers
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Ready to transcend traditional venture capital"
	subtitle="Join the shadow network"
	description="Strategic capital reserved for elite founders building category-defining companies. Your next funding round begins with a verified portfolio introduction."
	imageSrc="/generated/image-a-sophisticated-founder-in-their-late-40.webp"
	callsToAction={[
		{ href: "/contact", label: "Request introduction", variant: "primary" },
		{ href: "/portfolio", label: "View portfolio", variant: "secondary" }
	]}
/>
