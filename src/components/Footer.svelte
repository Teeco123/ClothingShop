<script lang="ts">
</script>

<footer>
	<div class="footer-links">
		<a href="/">Contact</a>
		<a href="/">Terms & Conditions</a>
		<a href="/">Shipping</a>
		<a href="/">Privacy</a>
	</div>
	<div class="newsletter">
		<div class="newsletter-box">
			<div class="newsletter-text">Subscribe to our newsletter!!</div>
			<div class="input-box">
				<input type="email" placeholder="EMAIL" />
				<button>+ </button>
			</div>
		</div>
		<div class="social-media">
			<a href="/">IG</a>
			<a href="/">FB</a>
			<a href="/">TW</a>
		</div>
	</div>
	<div class="rights">© 2023 Shop®. All rights reserved.</div>
</footer>

<style lang="scss">
	footer {
		margin: 15px auto 0px auto;
		.footer-links {
			display: flex;
			justify-content: center;
			a {
				text-decoration: none;
				font-size: 24px;
				margin: auto 15px;
			}
		}
		.newsletter {
			display: flex;
			border-bottom: solid black 2px;
			font-size: 28px;
			padding: 40px 10vw;
			.newsletter-box {
				display: flex;
				flex-direction: column;
				.input-box {
					display: flex;
					input[type='email'] {
						width: 400px;
						height: 40px;
						border: solid black 1px;
						border-right: none;
						font-size: 26px;
						padding: 0.5%;
						&:focus {
							outline: none;
							border: solid black 1px;
							border-right: none;
						}
					}
					button {
						width: 50px;
						background-color: white;
						border: solid black 1px;
						border-left: none;
						cursor: pointer;
						font-size: 28px;
					}
				}
			}
			.social-media {
				display: flex;
				align-items: center;
				margin-left: auto;
				order: 2;
				a {
					margin: 0px 15px;
					color: black;
					text-decoration: none;
				}
			}
		}
		.rights {
			display: flex;
			height: 70px;
			font-size: 23px;
			justify-content: center;
			align-items: center;
		}
	}
</style>
