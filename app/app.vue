<script>
import SimpleCounter from './cmps/SimpleCounter.vue'

export default {
    components: {
        SimpleCounter,
    }
}
</script>

<template>
    <h1>Hello Vue</h1>
    <SimpleCounter :start-from="9"/>
    <SimpleCounter :start-from="2"/>
    <SimpleCounter />

    <img src="/boy.png" alt="">
</template>

<style scoped>
header {
	line-height: 1.5;
}

.logo {
	display: block;
	margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
	header {
		display: flex;
		place-items: center;
		padding-right: calc(var(--section-gap) / 2);
	}

	.logo {
		margin: 0 2rem 0 0;
	}

	header .wrapper {
		display: flex;
		place-items: flex-start;
		flex-wrap: wrap;
	}
}
</style>
