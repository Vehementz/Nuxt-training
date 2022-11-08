<template>
    <div>
        <HeaderVue/>
        <input type="text" v-model="userId"/>
        <button @click="onLoadUser">Load User</button>
        <nuxt-child />
    </div>
</template>


<script>
import HeaderVue from '../components/Header.vue'

export default {
  components: { HeaderVue, HeaderVue },
  data() {
    return {
      userId: ''
    }
  },
  methods: {
    onLoadUser() {
      this.$router.push('/users/' + this.userId)
    }
  },
  layout: 'users'
}
</script>


<style scoped>

</style>