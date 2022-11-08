<template>
  <section class="container">
    <HeaderVue />
  </section>

</template>

<script>
import HeaderVue from '~/components/Header.vue';

    export default {
      components:  {
        HeaderVue
      },
      layout: 'users',
    }

</script>


<!-- <template>
  <div>
   <h1 style="text-align: center; color:red;">Hello</h1>
    <nuxt-link to="/users">Users</nuxt-link>
  <Tutorial/>
  </div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script> -->
