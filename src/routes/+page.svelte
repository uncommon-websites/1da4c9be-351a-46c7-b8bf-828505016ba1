<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";

	// Icons
	import IconBuilding from "~icons/lucide/building-2";
	import IconCompass from "~icons/lucide/compass";
	import IconLightbulb from "~icons/lucide/lightbulb";
	import IconLayers from "~icons/lucide/layers";
	import IconTarget from "~icons/lucide/target";
	import IconNetwork from "~icons/lucide/network";
</script>

<CustomerCardHero
	title="AI is transforming the future of work"
	subtitle="Enterprise case studies, implementation frameworks, and career transformation insights for leaders navigating AI adoption."
	customers={[
		{
			name: "Sarah Chen",
			position: "Chief People Officer",
			imageSrc: "/generated/image-editorial-environmental-portrait-of-a-co.webp"
		},
		{
			name: "Marcus Rodriguez",
			position: "VP of Transformation",
			imageSrc: "/generated/image-professional-woman-leader-in-a-modern-co.webp"
		},
		{
			name: "Elena Volkov",
			position: "Head of Learning & Development",
			imageSrc: "/generated/image-business-professional-in-a-thoughtful-po.webp"
		},
		{
			name: "James Patterson",
			position: "Director of Enterprise AI",
			imageSrc: "/generated/image-corporate-leader-portrait-in-a-real-offi.webp"
		},
		{
			name: "Aisha Okonkwo",
			position: "Chief Innovation Officer",
			imageSrc: "/generated/image-enterprise-executive-in-a-contemporary-s.webp"
		}
	]}
	callsToAction={[
		{
			href: "https://augintelligence.co",
			label: "Subscribe to insights"
		},
		{
			href: "/about",
			label: "Learn more"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/microsoft.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/salesforce.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/ibm.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/deloitte.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Augmented Intelligence bridges the gap between AI ambition and enterprise reality. We deliver proven implementation frameworks and transformation insights that help HR leaders, executives, and enterprise teams successfully navigate AI adoption—turning strategic uncertainty into confident, practical action."
/>

<Testimonials
	testimonials={[
		{
			name: "Priya Mehta",
			position: "Chief People Officer",
			company: "Enterprise Analytics Corp",
			quote:
				"Nelson's frameworks helped us roll out AI tools to 2,400 employees in 90 days instead of the projected six months. We avoided the costly mistakes that derailed our first attempt and saved over $400K in consulting fees.",
			image: "/generated/image-editorial-style-environmental-portrait-o.webp"
		},
		{
			name: "Marcus Washington",
			position: "VP of Transformation",
			company: "Global Financial Services",
			quote:
				"The enterprise case studies gave us confidence to move forward when our board was skeptical. We reduced implementation risk by learning from documented rollouts and cut our pilot phase from 12 weeks to 4 weeks.",
			image: "/generated/image-editorial-environmental-portrait-of-a-bl.webp"
		},
		{
			name: "Carmen Ruiz",
			position: "Head of Learning & Development",
			company: "TechCorp Industries",
			quote:
				"The career transformation frameworks helped us reskill 150 team members in three months. We retained 94% of our workforce through the AI transition instead of facing the costly turnover our competitors experienced.",
			image: "/generated/image-documentary-style-professional-headshot-.webp"
		}
	]}
/>

<Features
	title="Why Augmented Intelligence"
	subtitle="Practical insights from the frontlines of AI transformation, designed for leaders who need proven frameworks over theoretical advice."
	features={[
		{
			title: "Enterprise implementation frameworks",
			description:
				"Learn what the successful 20% of AI rollouts actually do. Get documented strategies that overcome the most common implementation barriers facing enterprise leaders today.",
			icon: IconBuilding
		},
		{
			title: "Career transformation guidance",
			description:
				"Navigate your career in an AI-augmented world with practical job search strategies and skill-building frameworks that prepare you for the future of work.",
			icon: IconCompass
		},
		{
			title: "Real practitioner insights",
			description:
				"Access learnings from building multiple AI-powered ventures simultaneously. No theory, just tactical decisions and systems that work in the real world.",
			icon: IconLightbulb
		},
		{
			title: "Five curated content pillars",
			description:
				"Subscribe to what matters to you. From enterprise briefs to technical deep-dives, each newsletter serves a specific audience need with targeted expertise.",
			icon: IconLayers
		},
		{
			title: "Working out loud philosophy",
			description:
				"Follow along as insights emerge from active consulting, workshops, and venture building. Get actionable guidance tested in real implementations, not abstract concepts.",
			icon: IconTarget
		},
		{
			title: "Integrated thought leadership",
			description:
				"Bridge insights across consulting engagements, keynote speaking, and startup building. One ecosystem connecting enterprise transformation with emerging AI capabilities.",
			icon: IconNetwork
		}
	]}
/>
<AboutTeaser />
<CallToAction 
	title="Don't let your competitors master AI transformation first"
	subtitle="Subscribe for proven frameworks"
	description="Every week, thousands of enterprise leaders get practical AI implementation insights that their competitors don't. Join CHROs, VPs of transformation, and L&D heads who turned implementation uncertainty into strategic advantage. Your peers are already moving—and they're documenting what works."
	imageSrc="/generated/image-a-confident-enterprise-executive-stands-.webp"
	callsToAction={[
		{
			href: "https://augintelligence.co",
			label: "Subscribe to insights",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Learn more",
			variant: "secondary"
		}
	]}
/>
