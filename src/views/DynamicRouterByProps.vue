<template>
  <div></div>
</template>

<script>
import axios from 'axios'
export default {
  props: ['id'],
  created () {
    // console.log(this.$route.params.id)
    console.log(this.id)
    // const seed = '475a6488a9fc69a5'
    // const seed = this.$route.params.id
    const seed = this.id
    axios.get(`https://randomuser.me/api/?seed=${seed}`).then(res => {
      console.log(res)
    })
  }
}
</script>
