<template>
 <section class="score">
    Player <span>{{this.winCount}}</span> <strong>x</strong> <span>{{this.loseCount}}</span> Computer
 </section>
</template>

<script>
    export default {
        props: ['winCount', 'loseCount']
    }

</script>

<style lang="scss">
    section.score{
        border-bottom: 1px solid #202020;
        padding: 2rem 0 ;
        font-size: 1.6rem;
        margin: 1rem 0;

        span {
            padding: .5rem;
            font-weight: bold;
            border: 2px solid #202020;
            margin: 0 8px;
        }
    }
</style>

