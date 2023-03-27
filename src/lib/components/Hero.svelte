<div class="grid grid-cols-2 card-container">
	<div class="left-card">
		<img class="" src="./funny-owl-sq-ed.jpg" alt="funny owl" />

		<div class="card-bg" />
	</div>

	<div class="flex right-card">
		<div class="card-bg" />
		<div class="inside-body">
			<h1 class="center right-inside-body">
				<span class="super-accent-text">WHO</span>
				<!-- <br /> -->
				needs help?
			</h1>
			<h2 class="center right-inside-body">Looking for a solution?</h2>
			<h2 class="center right-inside-body">Some customer service?</h2>
			<h2 class="center right-inside-body">A new website?</h2>
		</div>
	</div>
</div>

<style lang="scss">
	p {
		a {
			color: red;
		}
	}

	/* .owl {
		background-image: url('./funny-owl-sq-ed.jpg');
		background-image: cover;
	} */

	h1 {
		font-size: var(--step-5);
	}

	h2 {
		font-size: var(--step-1);
	}

	.super-accent-text {
		font-family: var(--ff-super-accent);
		font-size: var(--step-8);
	}

	.center {
		text-align: center;
	}
	.right-inside-body {
		padding-bottom: var(--em-size-12);
	}

	.card-bg {
		position: absolute;
		background-color: var(--clr-neutral-900);
		transform: rotate(355deg);

		left: 0;
		right: 0;
		bottom: 0;
		top: 0;
		border-radius: 25px;
		z-index: -2;
	}

	.left-card {
		position: relative;
	}
	.right-card {
		/*padding: var(--em-size-32); */
		flex-direction: column;
		align-items: center;
		justify-content: space-around;
		background-color: var(--clr-lite-accent);
		border-radius: 25px;
		position: relative;
	}

	.card-container {
		gap: var(--size-44);
		margin: 0 auto;
		/*max-width: 1019px;  */
		/*padding: var(--size-44) 0; */
		padding: var(--size-36);
	}

	img {
		width: 100%;
		border-radius: 25px;
		position: relative;
	}

	.card-text-large {
		font-weight: bold;
		font-size: 8rem;
	}

	.card-text-medium {
		font-size: var(--fs-700);
		font-weight: bold;
	}

	.card-text-small {
		font-size: var(--fs-600);
	}
</style>
