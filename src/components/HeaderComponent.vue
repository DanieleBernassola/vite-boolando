<script>
export default {
  name: 'Header'
}
</script>

<template>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css"
    integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />
  <header>
    <div class="container position-fixed">
      <div class="row align-items-center">
        <div class="col-25 text-align-left">
          <ul>
            <li><a href="">Donna</a></li>
            <li><a href="">Uomo</a></li>
            <li><a href="">Bambini</a></li>
          </ul>
        </div>
        <div class="col-50 text-align-center">
          <img class="logo" src="/img/boolean-logo.png" alt="logo">
        </div>
        <div class="col-25 text-align-right text-white">
          <i class="fa-regular fa-user"></i>
          <i class="fa-regular fa-heart"></i>
          <i class="fa-solid fa-bag-shopping"></i>
        </div>
      </div>
    </div>
  </header>
</template>

<style lang="scss">
@use '../src/assets/styles/main.scss';
</style>