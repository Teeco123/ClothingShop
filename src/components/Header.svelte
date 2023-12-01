<script lang="ts">
</script>

<header>
	<div class="logo">LOGO</div>
	<div class="cart">CART</div>
	<div class="navbar">
		<a href="/">GOWNO</a>
		<a href="/">GOWNO</a>
		<a href="/">GOWNO</a>
		<a href="/">GOWNO</a>
	</div>
</header>

<style lang="scss">
	header {
		width: auto;
		height: 140px;
		padding: 0px 20%;
		border-bottom: 2px solid black;
		display: grid;
		grid-template-columns: 1fr auto 1fr;
		grid-template-rows: auto 30%;
		align-items: center;
		background-color: white;
		.logo {
			grid-column: 2;
			text-align: center;
		}
		.cart {
			grid-column: 3;
			grid-row: 1 / span 2;
			text-align: right;
		}
		.navbar {
			grid-column: 1 / span 3;
			grid-row: 2;
			text-align: center;
			word-spacing: 5px;
			a {
				text-decoration: none;
				color: black;
				&:hover {
					color: #959595;
					text-decoration: underline;
				}
			}
		}
	}
</style>
