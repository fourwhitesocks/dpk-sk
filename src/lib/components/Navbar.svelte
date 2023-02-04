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
		<svg class="circle-image" height="200" width="200">
			<circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="white" />
		</svg>
		<div class="contact">Contact Me</div>
	</div>
</header>

<style lang="scss">
	.header {
		background-color: var(--clr-neutral-900);
	}
	.nav-container {
		max-width: var(--wrapper);
		margin-inline: auto;
		padding: 1em 2em;
		justify-content: space-between;

		.logo-text {
			color: var(--clr-neutral-100);
			font-weight: var(--fw-700);
		}
		.contact {
			color: var(--red-400);
		}
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
		top: -28px;
		right: -132px;
	}
	/* .circle-image {
		-webkit-mask-image: url('circle.svg');
		-webkit-mask-size: cover;
		-webkit-mask-repeat: no-repeat;
		-webkit-mask-position: bottom;
		z-index: -1;
	} */
</style>
