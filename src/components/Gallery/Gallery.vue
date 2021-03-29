<template>
    <div class="galleryWrapper">
        <h3>My Portfolio</h3>
        <h6>Web & App</h6>
        <gallery-images></gallery-images>
    </div>
</template>

<script>
import GalleryImages from './GalleryImages/GalleryImages.vue';

export default {
    components:{GalleryImages}
}
</script>

<style scoped>
    .galleryWrapper{
        width: 70%;
        margin: auto;
        text-align: center;
    }
    .galleryWrapper > h3{
        font-family: 'Open Sans';
        font-size: 35px;
        font-weight: 500;
    }
    .galleryWrapper > h6{
        font-family: 'Open Sans';
        font-size: 18px;
        font-weight: normal;
        color: #202020;
        opacity: 50%;
    }
</style>