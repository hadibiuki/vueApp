<template>
    <div class="commentWrapper">
        <h3>Valuable Testimonial</h3>
        <h6>See People Say About Me</h6>
        <div class="backgroundSlide"></div>
        <splide :options="options">
            <splide-slide>
                <slider-item></slider-item>
            </splide-slide>
            <splide-slide>
                <slider-item></slider-item>
            </splide-slide>
            <splide-slide>
                <slider-item></slider-item>
            </splide-slide>
        </splide>
      
    </div>
</template>

<script>
import { Splide, SplideSlide } from '@splidejs/vue-splide';
import '@splidejs/splide/dist/css/themes/splide-default.min.css';
import SliderItem from './SlderItem/SliderItem.vue';

export default {
    components: {Splide,SplideSlide,SliderItem},
      data() {
        return {
            options: {
            rewind : true,
            height: 550,
            arrows : false,
            },
        };
    },
}
</script>

<style scoped>
    .commentWrapper{
        width: 70%;
        margin: auto;
        text-align: center;
        margin-top: 150px;
        position: relative;
    }
    .commentWrapper > h3{
        font-family: 'Open Sans';
        font-size: 35px;
        font-weight: 500;
    }
    .commentWrapper > h6{
        font-family: 'Open Sans';
        font-size: 18px;
        font-weight: normal;
        color: #202020;
        opacity: 50%;
    }

    .backgroundSlide{
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        left: 8%;
        background: var(--perpel);
        width: 84%;
        height: 350px;
        z-index: -1;
    }
    /* .slider{ */
        /* width: 600px;
        height: 200px;
        margin: auto;
        margin-top: 100px; */

    /* } */
</style>