<script lang="ts">
	import {
		Anchor,
		Button,
		Center,
		Container,
		Figure,
		Heading,
		Stack,
		Text,
	} from "@kahi-ui/framework";
	import { LinkedinIcon, GithubIcon, TwitterIcon, InstagramIcon } from "svelte-feather-icons";
</script>

<Stack.Container
	spacing="medium"
	orientation="horizontal"
	alignment="center"
	margin_top="huge"
	padding_left="mobile:large"
>
	<Figure max_size="nano" shape="circle">
		<img src="head.jpeg" alt="Louis Birla with Goggles in a Theater" />
	</Figure>
	<Stack.Container>
		<Text is="i">loo-ee</Text>
		<Heading variation="block">Louis Birla</Heading>
		<Text>Student • Developer • Worldbuilder</Text>
	</Stack.Container>
</Stack.Container>
<Stack.Container orientation="horizontal" alignment="center" spacing="small">
	<Anchor href="https://www.linkedin.com/in/louisbirla/" target="_blank">
		<Button palette="informative">
			<LinkedinIcon size="24" />
		</Button>
	</Anchor>
	<Anchor href="https://github.com/louisbirla" target="_blank">
		<Button palette="dark">
			<GithubIcon size="24" />
		</Button>
	</Anchor>
	<Anchor href="https://twitter.com/louisbirla" target="_blank">
		<Button palette="alert">
			<TwitterIcon size="24" />
		</Button>
	</Anchor>
	<Anchor href="https://www.instagram.com/louisbirla/" target="_blank">
		<Button palette="negative">
			<InstagramIcon size="24" />
		</Button>
	</Anchor>
</Stack.Container>
<Container>
	<Heading is="h2">Howdy 👋</Heading>
	<Text>I'm Louis, a student and developer with many passions and interests.</Text>
	<Heading is="h3" margin_top="medium">Academics 🎓</Heading>
	<Text
		>I'm a Freshman at Texas A&M at College Station! I'm an engineering major hoping to get into the
		computer engineering program.</Text
	>
	<!-- <Text>I graduated from Lake Travis High School.</Text> -->
	<Heading is="h3" margin_top="medium">Work 💼</Heading>
	<Text
		>I'm looking for programming jobs as a web-developer, since I have been programming since the
		5th grade, 7 years ago! I'm an expert at web technologies and am <Anchor
			href="https://www.linkedin.com/in/louisbirla/details/skills/"
			target="_blank"
			palette="informative">certified by LinkedIn</Anchor
		>.</Text
	>
	<Stack.Container orientation="horizontal" spacing="small" margin_top="medium">
		<Anchor href="https://www.upwork.com/freelancers/louisbirla" target="_blank">
			<Button palette="affirmative">UpWork</Button>
		</Anchor>
		<Anchor href="https://www.fiverr.com/louisbirla" target="_blank">
			<Button palette="negative">Fiverr</Button>
		</Anchor>
		<Anchor
			href="https://www.peopleperhour.com/freelancer/technology-programming/louis-birla-full-stack-capable-programmer-jvmwnjj"
			target="_blank"
		>
			<Button palette="alert">peopleperhour</Button>
		</Anchor>
	</Stack.Container>
	<Heading is="h4" margin_top="medium">Experience 📚</Heading>
	<Text
		>In 2020 and 2021, I founded and led the startup <Anchor
			href="https://loop.birla.io"
			target="_blank"
			palette="affirmative">Loop</Anchor
		> to MVP. The team included professional designers and developers, a large project for a High School
		student. Since then, I have decided to temporarily pause the project in order to focus on my academics.</Text
	>
</Container>
<Center margin_top="large">
	<Text is="small">© Louis Birla</Text>
</Center>
