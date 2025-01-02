<template>
	<div class="nav-bar">
		<router-link
			class="products-link"
			to="/products"
		>
			<div class="logo-wrap">
				<img :src="logo" />
			</div>
		</router-link>

		<router-link
			class="cart-link"
			to="/cart"
		>
			<button>Shopping Cart</button>
		</router-link>
	</div>
</template>

<script>
	import logo from '@/assets/logo-hexagon.svg';
	export default {
		name: 'NavBar',
		data() {
			return {
				logo,
			};
		},
	};
</script>
