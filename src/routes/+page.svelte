<script lang="ts">
	import Footer from '../components/Footer.svelte';
	import Header from '../components/Header.svelte';
</script>

<body>
	<Header />
	<div class="big-img"><img src="background.jpg" alt="" /></div>
	<div class="items-grid">
		<div class="item">
			<img src="hoodie.webp" alt="" />
			<div class="item-info">
				<div class="item-name">HELLSPAWN HOODIE</div>
				<div class="item-price">$70.00 USD</div>
			</div>
		</div>
		<div class="item">
			<img src="hoodie.webp" alt="" />
			<div class="item-info">
				<div class="item-name">HELLSPAWN HOODIE</div>
				<div class="item-price">$70.00 USD</div>
			</div>
		</div>
		<div class="item">
			<img src="hoodie.webp" alt="" />
			<div class="item-info">
				<div class="item-name">HELLSPAWN HOODIE</div>
				<div class="item-price">$70.00 USD</div>
			</div>
		</div>
		<div class="item">
			<img src="hoodie.webp" alt="" />
			<div class="item-info">
				<div class="item-name">HELLSPAWN HOODIE</div>
				<div class="item-price">$70.00 USD</div>
			</div>
		</div>
		<div class="item">
			<img src="hoodie.webp" alt="" />
			<div class="item-info">
				<div class="item-name">HELLSPAWN HOODIE</div>
				<div class="item-price">$70.00 USD</div>
			</div>
		</div>
		<div class="item">
			<img src="hoodie.webp" alt="" />
			<div class="item-info">
				<div class="item-name">HELLSPAWN HOODIE</div>
				<div class="item-price">$70.00 USD</div>
			</div>
		</div>
	</div>
	<Footer />
</body>

<style lang="scss">
	@import url('https://fonts.googleapis.com/css2?family=AR+One+Sans:wght@500&family=Roboto:wght@300&display=swap');
	:global(body) {
		margin: 0;
		font-family: 'Roboto';
		.big-img {
			width: auto;
			height: 85vh;
			border-bottom: 2px solid black;
			img {
				width: 100%;
				height: 100%;

				object-fit: cover;
			}
		}
		.items-grid {
			display: grid;
			justify-items: center;
			align-items: center;
			grid-template-columns: repeat(4, 1fr);
			row-gap: 20px;
			margin-top: 10px;
			padding-bottom: 30px;
			border-bottom: 2px solid black;
			.item {
				img {
					width: 100%;
					scale: 95%;
					transition: scale 0.8s;
				}
				.item-info {
					text-align: center;
					font-size: 1.2vw;
					.item-name {
						text-decoration: none;
					}
					.item-price {
						margin-top: 10px;
					}
				}
			}

			.item:hover > img {
				scale: 100%;
			}

			.item:hover > .item-info > .item-name {
				text-decoration: underline;
			}
		}

		&::-webkit-scrollbar {
			width: 5px;
		}

		&::-webkit-scrollbar-track {
			box-shadow: inset 0 0 5px rgb(198, 198, 198);
			border-radius: 10px;
		}

		&::-webkit-scrollbar-thumb {
			background: #888888;
			border-radius: 10px;
		}
	}
</style>
