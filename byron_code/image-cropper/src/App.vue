<template>
    <div class="container">
        <app-header></app-header>
        <hr>
        <div class="row">
            <cropper></cropper>
            <app-crop-details></app-crop-details>
        </div>
        <hr>
        <app-footer></app-footer>
    </div>
</template>

<script>
    import Header from './components/Shared/Header.vue';
    import Footer from './components/Shared/Footer.vue';
    import Cropper from './components/ImageCropper/Cropper.vue';
    import CropDetails from './components/ImageCropper/CropDetails.vue';

    export default {
        components: {
            appHeader: Header,
            'cropper': Cropper,
            'app-crop-details': CropDetails,
            'app-footer': Footer
        }
    }
</script>

<style>

</style>
