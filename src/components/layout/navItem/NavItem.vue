<template>
    <button v-if="isBut">
        <slot></slot>
    </button>
    <h6 v-else>
        <slot></slot>
    </h6>
</template>

<script>
export default {
    props:{ 
        isBut: {
                type: Boolean,
                required: false,
                default: false
            }, 
        }
}
</script>

<style scoped>
h6{
    font-family: 'Open Sans';
    font-size: 15px;
    font-weight: 500;
    margin-right: 20px;
    color: var(--black);
    padding: 0.75rem .9rem;

}
button{
    background: var(--perpel);
    color: var(--white);  
    padding: 0.75rem 1.5rem;
    border:none;
    outline: none;
    color: white;
    cursor: pointer;
    border-radius: 30px;
}
</style>

