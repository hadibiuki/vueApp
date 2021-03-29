<template>
    <div  class="slider">
        <div class="imgWrapper">
            <img src="../../../assets/image/protopolio.png" alt="">
        </div>
        <h6>Jhon Wick, New York</h6>
        <p>Writing paragraphs takes practice, but what should students write about? Good paragraph writing prompts allow students to write about what they know and like, so their focus can be on the writing process and using the four essential elements.</p>
    </div>
</template>

<style>
    button.is-active{
        background: var(--perpel)!important;
    }
</style>

<style scoped>
    .slider{
        width: 80%;
        height: 400px;
        margin: auto;
        margin-top: 40px;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        box-shadow: 0px 5px 10px #00000010;
        background: var(--white);

    }
    .imgWrapper{
        background:#754EF999;
        border-radius: 50%;
        width: 140px;
        height: 140px;
        /* margin: auto; */
        display: flex;
         justify-content: center;
        align-items: center;
        padding: 20px;
    }
    .slider img{
        width: 120px;
        height: 120px;
        border: 10px solid var(--perpel);
        border-radius: 50%;
        padding: 0;
    }
    .slider h6{
        font-family: 'Open Sans';
        font-size: 18px;
        font-weight: 500;
        margin: 20px
    }

    .slider p{
        font-family: 'Open Sans';
        font-size: 14px;
        font-weight: normal;
        opacity: 50%;
        width: 80%;
    }

</style>