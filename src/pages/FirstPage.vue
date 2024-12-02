<template>
	<header class="header m-10 flex justify-center">
		<img src="../assets/black-logo.svg" alt="" />
	</header>
	<main class="main">
		<div
			class="welcome flex flex-col gap-10 justify-center relative items-center min-h-[70vh]"
		>
			<h2 class="font-main text-2xl text-center w-auto sm:text-4xl">
				Начни экономить и накоплять деньги!
			</h2>
			<div class="header-currency flex gap-14 sm:gap-24">
				<p class="text-6xl font-currency">$</p>
				<p class="text-6xl font-currency">€</p>
				<p class="text-6xl font-currency">₽</p>
			</div>
			<button class="bg-stone-950 text-white px-10 py-2.5 rounded-full font-main">
				Продолжить
			</button>
		</div>
	</main>
</template>

<script setup lang="ts"></script>

<style lang="scss" scoped></style>
