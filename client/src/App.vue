<script setup>
import Navbar from './components/Navbar.vue';
import HomePage from './pages/HomePage.vue';

</script>

<template>
  <header>
    <Navbar />
  </header>
  <main class="d-flex align-items-center">
    <HomePage />
  </main>
  <footer>
    <div class="col-12">
      <div class="d-flex justify-content-around p-4">
        <a href=" https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs">HTML & CSS</a>
        <a href=" https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs">Semantic Markup</a>
        <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs">Responsive Design</a>
        <a href="https://www.youtube.com/watch?v=dQw4w9WgXcQ&pp=ygUJcmljayByb2xs">Accessibility
          Standards</a>
      </div>
    </div>
    <div class="col-12">
      <div class="lower-footer d-flex p-4 justify-content-center">
        <div class="d-block">
          <p class="fs-2 fw-semibold d-flex justify-content-center">From Ideas to Reality</p>
          <p>If you can dream it then you can build it with technology solutions.</p>
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
}

footer {
  background-color: #F4F6F8;
}
</style>
