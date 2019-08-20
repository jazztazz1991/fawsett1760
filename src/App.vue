<template>
  <div id="app">
    <app-header></app-header>
    <app-addressImage></app-addressImage>
      <h1 class="title">ABOUT</h1>
    <app-about></app-about>
      <h1 class="title">GALLERY</h1>
    <app-gallery></app-gallery>
      <h1 class="title">FEATURES</h1>
    <app-features></app-features>
      <h1 class="title">CONTACT</h1>
    <app-contact></app-contact>
  </div>
</template>

<script>
    import header from './components/header.vue';
    import addressImage from './components/addressImage.vue';
    import gallery from './components/gallery.vue';
    import about from './components/about.vue';
    import features from './components/features.vue';
    import contact from './components/contact.vue';
    
    export default {
      name: 'app',
      components: {
          'app-header': header,
          'app-addressImage': addressImage,
          'app-gallery': gallery,
          'app-about': about,
          'app-features': features,
          'app-contact': contact,
      }
    }
</script>

<style>
    .title{
        text-align: center;
        font-size: 45px;
        border-bottom: 3px solid #f8bf21;
        width: 250px;
        display: block;
        margin-left: auto;
        margin-right: auto;
    }
    hr{ 
        height: 1px;
        color: #f8bf21;
        background-color: #f8bf21;
        border: none;
        clear: both;
    }
</style>
