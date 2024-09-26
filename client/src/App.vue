<script setup>
import Navbar from './components/Navbar.vue';

</script>

<template>
  <header>
    <Navbar />
  </header>
  <main>
    <router-view />
  </main>
  <footer>
    <div class="row">
      <div class="col-12">
        <div class="d-flex m-3 pb-3 justify-content-around ">
          <a href=" https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs">HTML & CSS</a>
          <a href=" https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs">Semantic Markup</a>
          <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs">Responsive Design</a>
          <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs">Accessibility
            Standards</a>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col-12">
        <div class="lower-footer d-flex justify-content-center">
          <div class="d-block">
            <p class="fs-2 fw-semibold">From Ideas to Reality</p>
            <p>If you can dream it then you can build it with technology solutions.</p>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style lang="scss">
@import '@/assets/scss/main.scss';

main {
  background-color: #061130;
}

.lower-footer {
  background-color: #dedede;
  height: 25vh;
}

footer {
  height: 20vh;
  background-color: #F4F6F8;

}
</style>
