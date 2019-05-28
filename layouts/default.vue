<template>
  <div>
    <TheHeader/>
    <main class="contents">
      <nuxt/>
      <TheForm/>
    </main>
    <TheFooter/>
  </div>
</template>

<script>
  import TheHeader from '~/components/common/TheHeader';
  import TheFooter from '~/components/common/TheFooter';
  import TheForm from '~/components/common/TheForm';

  export default {
    components: {
      TheHeader,
      TheFooter,
      TheForm
    }
  }
</script>
<style>
body{
  background: url('~@/assets/images/bg.jpg') fixed;
}
</style>
