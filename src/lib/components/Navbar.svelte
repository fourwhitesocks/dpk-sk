<script>
	import LogoLight from '$lib/components/LogoLight.svelte';
	import Circle from '$lib/components/Circle.svelte';
</script>

<header class="header">
	<div class="nav-container flex">
		<div class="flex horz-align">
			<div class="logo-graphic"><LogoLight /></div>
			<div class="logo-text">DIGITAL PAIN KILLERS</div>
		</div>
		<div class="contact">Questions?</div>
	</div>

	<svg
		width="130"
		height="130"
		viewBox="0 0 130 130"
		fill="none"
		xmlns="http://www.w3.org/2000/svg"
	>
		<circle id="contact-circle" cx="65" cy="65" r="65" fill="white" />
	</svg>
</header>

<style lang="scss">
	.header {
		background-color: var(--clr-neutral-900);
		position: relative;
	}
	.nav-container {
		max-width: var(--wrapper);
		margin-inline: auto;
		padding: 1em 2em;
		justify-content: space-between;
		position: relative;

		.logo-text {
			color: var(--clr-neutral-100);
			font-weight: var(--fw-700);
		}
	}

	.contact {
		color: var(--clr-neutral-900);
		font-weight: var(--fw-700);
		z-index: 4;
		position: absolute;
		left: 89%;
		top: 35px;
	}
	.logo-text {
		font-size: var(--fs-550);
		font-weight: bolder;
		color: var(--clr-neutral-100);
		z-index: 3;
	}
	.horz-align {
		align-items: center;
	}

	svg {
		position: absolute;
		height: 163px;
		width: 163px;
		/*top: -31px;
		right: -31px; */
	}
	/* .circle-image {
		-webkit-mask-image: url('circle.svg');
		-webkit-mask-size: cover;
		-webkit-mask-repeat: no-repeat;
		-webkit-mask-position: bottom;
		z-index: -1;
	} */
</style>
