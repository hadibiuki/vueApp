<template>
    <div class="cardWrapper">
        <card iconImg="stopwatch.svg" title="On time" desc="All i want to have client setisfaction & this is my aim"></card>
        <card iconImg="safe-box.svg" title="Clean work" ></card>
        <card iconImg="check.svg" title="Client setisfaction" ></card>
    </div>

</template>

<script>
import Card from '../CardInfo/Card/Card.vue';
// import Card2 from '../../assets/icon/in.svg';

export default {
    components:{Card}
}
</script>

<style  scoped>
    .cardWrapper{
        display: flex;
        flex-direction: row;
        width: 60%;
        margin: 150px auto;
    }
</style>

