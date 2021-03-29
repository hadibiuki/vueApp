<template>
    <footer>
        <div class="footerWrapper">
            <h1>Portfolio</h1>
            <nav>
                <nav-item>ABOUT ME</nav-item>
                <nav-item> PORTFOLIO</nav-item>
                <nav-item>DOWNLOAD CV</nav-item>
            </nav>
            <div>
                <img src="../../assets/icon/FacebookWhite.svg" alt="">
                <img src="../../assets/icon/twiiterWite.svg" alt="">
                <img src="../../assets/icon/LinkedinIcon.svg" alt="">
            </div>
        </div>
    </footer>
</template>

<script>
import NavItem from './navItem/NavItem.vue';

export default {
    components:{NavItem}
}
</script>

<style scoped>
    footer{
        background: var(--perpel);
        width: 100vw;
    }
    .footerWrapper{
        width: 80%;
        margin: auto;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        padding: 20px 10px ;
        color: var(--white);
    }

    .footerWrapper h1{
        font-family: 'Trebuchet MS';
        font-size: 35px;
        font-weight: bold;
    }
    .footerWrapper div img{
        /* background: var(--white); */
        margin-left: 20px;
        width: 19px;
        height: 19px;
    }

    nav{
        display: flex;
        position: relative;
        flex-direction: row;
        align-items: center;
        padding: 20px;
        margin: auto;
        z-index: 10;
    }

    nav h6{
        color: var(--white);
        font-size: 10px;
        font-weight: normal;
    }
</style>