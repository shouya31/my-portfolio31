<template>
  <nav
    class="navbar highlight-background has-background-black header-style-fixed"
    role="navigation"
    aria-label="main navigation"
  >
    <NuxtLink to="/" class="title is-3" style="color: floralwhite;">MY PORTFOLIO</NuxtLink>
    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button highlight-background has-background-black">
            <NuxtLink to="/about" class="has-text-weight-bold has-text-white">WORKS</NuxtLink>
          </a>
          <a class="button highlight-background has-background-black">
            <NuxtLink to="/" class="has-text-weight-bold has-text-white">CONTACT</NuxtLink>
          </a>
          <a href="https://github.com/shouya31" class="button highlight-background has-background-black has-text-weight-bold has-text-white">
            MY Github
          </a>
        </div>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  transition: 'bounce'
}
</script>


<style>
.header-style-fixed {
  position: fixed;
  width: 100%;
}
.highlight-background {
  opacity: 0.5;
}
.page-leave-active {
  transition: opacity 0.5s;
}
.page-enter-active{
  transition: opacity 1.5s;
}
.page-enter,
.page-leave-active {
  opacity: 0;
}
.bounce-enter-active {
  animation: bounce-in 0.8s;
}
.bounce-leave-active {
  animation: bounce-out 0.5s;
}
@keyframes bounce-in {
  0% {
    transform: scale(0);
  }
  50% {
    transform: scale(1.5);
  }
  100% {
    transform: scale(1);
  }
}
@keyframes bounce-out {
  0% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.5);
  }
  100% {
    transform: scale(0);
  }
}
</style>
