<template>
    <section class="universalHero">
        <h1>SUPERLARGE<br /><slot></slot></h1>
    </section>
</template>

<style lang="sass">
.universalHero
    padding-top: 6rem
    padding-bottom: 6rem
    text-align: center
    font-size: clamp(1.5rem, 2vw + 1rem, 2.25rem)
    background: var(--primary)
</style>
