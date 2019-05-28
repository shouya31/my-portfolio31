<template>
  <div class="container">
    <h1 class="title">About page</h1>
    <WorkItem />
  </div>
</template>
<script>
import WorkItem from '~/components/SessionComponents/WorkItem'
export default {
  transition: 'bounce',
  components: {
   WorkItem
  },
}
</script>