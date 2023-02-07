<div class="grid grid-cols-2 card-container">
	<div class="left-card">
		<img class="" src="./funny-owl-sq-ed.jpg" width="" alt="funny owl" />
		<div class="card-bg" />
	</div>

	<div class="flex right-card">
		<div class="card-bg" />
		<div class="inside-body">
			<div class="center card-text-medium">
				<span class="card-text-large">WHO</span><br />
				needs help?
			</div>
			<div class="center card-text-small">Looking for a solution?</div>
			<div class="center card-text-small">Some customer service?</div>
			<div class="center card-text-small">A new website?</div>
		</div>
	</div>
</div>

<style lang="scss">
	p {
		a {
			color: red;
		}
	}

	.center {
		text-align: center;
	}
	.inside-body {
		padding: var(--em-size-8);
	}

	.card-bg {
		position: absolute;
		background-color: lime;
		transform: rotate(-6deg) skewX(0deg) skewY(0deg) scaleY(1.1) scaleX(1);

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
		max-width: 1019px;
		padding: var(--size-44) 0;
	}

	img {
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
