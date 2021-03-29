<template>
    <div class="hierWrapper">
        <h3>Want To Hire Me?</h3>
        <h6>If You Like My Work</h6>

        <div class="formWrapper">
            <input type="text" placeholder="enter your email" v-model.trim="email">
            <button>Hire Me</button>
        </div>

    </div>
</template>

<script>
export default {
     data() {
        return {
            email:''  
        }
    }
}
</script>

<style scoped>
    .hierWrapper{
        width: 70%;
        margin: auto;
        text-align: center;
        margin-top: 150px;
    }
    .hierWrapper > h3{
        font-family: 'Open Sans';
        font-size: 35px;
        font-weight: 500;
        margin-bottom: 10px;
    }
    .hierWrapper > h6{
        font-family: 'Open Sans';
        font-size: 18px;
        font-weight: normal;
        color: #202020;
        opacity: 50%;
    }


    .formWrapper{
        margin: 50px auto 150px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    input{
        width: 500px;
        height: 50px;
        padding: 20px;
        outline: none;
        border: 1px solid var(--perpel);
        font-family: 'Open Sans';
        font-size: 12px;
        font-weight: normal;
    }
    
    button{
        background: var(--perpel);
        color: var(--white);
        width: 180px;
        height: 50px;
    }
    
</style>