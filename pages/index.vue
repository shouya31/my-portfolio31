<template>
  <div>
    <Top/>
    <MyProfile v-if="anime1"/>
    <CardItem/>
  </div>
</template>

<script>
import CardItem from '~/components/SessionComponents/CardItem'
import Top from '~/components/SessionComponents/Top'
import MyProfile from '~/components/SessionComponents/MyProfile'
export default {
  components: {
    CardItem,
    Top,
    MyProfile
  },
  data() {
    return {
      anime1: true
    }
  }
}
</script>
