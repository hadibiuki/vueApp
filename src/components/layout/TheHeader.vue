<template>
    <header>
        <div class="Backwite"></div>
        <section class="nav">
            <h3>Portfolio</h3>
            <nav>
                <nav-item>ABOUT ME</nav-item>
                <nav-item> PORTFOLIO</nav-item>
                <nav-item isBut>DOWNLOAD CV</nav-item>
            </nav>
        </section>
        <section class="intro">
            <div class="imgContainer">
                <img src="../../assets/image/protopolio.png" alt="">
            </div>
            <div class="textIntro">
                <div class="myWork">
                    <h1>MY</h1>
                    <div class="singleContent">
                        <div class="rectangle"></div>
                        <h1 class="singleWord">W</h1>
                        <h1 class="singleWord">
                            <span></span>
                            O</h1>
                        <h1 class="singleWord">R</h1>
                        <h1 class="singleWord">K</h1>
                    </div>
                </div>
                <h6>Web & visual Designer</h6>
            </div>
        </section>
        <section>
            <div class="myINtro">
                <div>
                    <img src="../../assets/icon/play-button.svg" alt="">
                </div>
                <h6>MY INTRO</h6>
            </div>
        </section>
        <section>
            <div class="social">
                <h6>FOLLOW ME ON :</h6>
                <div></div>
                <img src="../../assets/icon/facebook.svg" alt="">
                <img src="../../assets/icon/twitter.svg" alt="">
                <img src="../../assets/icon/in.svg" alt="">
                
            </div>

            <h6 class="creative">BE CREATIVE</h6>
        </section>
    </header>
</template>

<script>
import NavItem from './navItem/NavItem.vue';

export default {
    components:{NavItem}
}
</script>

<style scoped>
    header{
        background: var(--perpel);
        width: 100vw;
        height: 100vh;
        position: relative;
        z-index: 1;
    }
    .Backwite{
        background:var(--white);
        position: absolute;
        width: 70%;
        height: 96vh; 
        top: 0;
        right: 0;
        z-index: -1;   
    }
    .nav,.intro{
        display: flex;
        position: relative;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
        justify-content: space-between;
        padding: 20px;
        width: 80%;
        margin: auto;
        z-index: 10;
    }
    .nav h3{
        font-family: 'Trebuchet MS';
        font-weight: bold;
        font-size: 35px;
        color: var(--white);
    }
    nav{
        display: flex;
        flex-direction: row;
        align-items: row;
    }
    .intro{
        margin-top: 10px;
    }
    .intro img{
        border:20px solid var(--perpel);
        border-radius: 50%;
    }
    .imgContainer{
        background: var(--white);
        border-radius: 50%;
        padding: 40px;
        border: 20px solid var(--perpel);

        /* transform: translate(-50%,-50%) */
    }

    .textIntro{
        display: flex;
        flex-direction: column;
        margin-right: 150px;
    }
    .myWork {
        display: flex;
        flex-direction: row;
    }
    .singleContent{
        display: flex;
        flex-direction: row;
        position: relative;
    }
    .myWork h1{
        font-family: 'Trebuchet MS';
        font-size: 100px;
        font-weight: bold;
    }
    .myWork> h1{
        margin-right: 30px;
    }

    .myWork h1.singleWord{
        color: var(--perpel);
    }

    .rectangle{
        position: absolute;
        width: 100%;
        height: 15px;
        box-shadow: 0px 3px 6px #00000016;
        top: 50%;
        transform: translateY(-50%);
    }

    h1 span{
        background: var(--white);
        width: 30px;
        height: 15px;
        position: absolute;
        top: 50%;
        transform: translateY(-50%);

    }

    .textIntro h6{
        text-align: center;
        font-family: 'Open Sans';
        font-weight: 500px;
        font-size: 25px;
    }


    .myINtro{
        position: absolute;
        top: 70%;
        right: 25%;
        z-index: 10px;
        display: flex;
        flex-direction: row;
        align-items: center;
    }

    .myINtro div{
        box-shadow: 0px 5px 5px #754EF916;
        padding: 20px;
        border-radius: 50%;
        width: 70px;
        height: 70px;
        display: flex;
        align-self: center;
        justify-content: center;
        margin-right: 20px;
    }
    .myINtro h6{
        font-family: 'Open Sans';
        font-weight: 500px;
        font-size: 16px;
    }

    .social{
        position: absolute;
        top: 50%;
        right: 10px;
        transform: translateY(-50%);
        display: flex;
        flex-direction: column;
        align-items: center;
    }
    .social h6{
        font-family: 'Open Sans';
        font-weight: 500px;
        font-size: 18px; 
        transform: rotate(90deg);
        color: var(--perpel);
        /* display: inline; */
        margin-bottom: 80px;
    }
    .social div{
        width: 1px;
        height: 50px;
        background: var(--perpel);
        margin-bottom: 30px;

    }
    .social img{
        width: 20px;
        height: 20px;
        margin-bottom: 30px;
    }
    .creative{
         font-family: 'Open Sans';
        font-weight: 500px;
        font-size: 16px;
        color: var(--white);
        margin-left: 20%;
        margin-top: 20px;
    }
</style>