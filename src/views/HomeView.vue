<template>
  <div class="home">
    <HeaderMiruku/>
    <CarouselHomeMiruku/>
  </div>
</template>

<script>
// @ is an alias to /src
import HeaderMiruku from '@/components/HeaderMiruku.vue';
import CarouselHomeMiruku from '@/components/CarouselHomeMiruku.vue';

export default {
  name: 'HomeView',
  components: {
    HeaderMiruku,
    CarouselHomeMiruku
  }
}
</script>
