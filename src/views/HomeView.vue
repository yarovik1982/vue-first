<template>
  <div class="home">
    <form-login/>
  </div>
</template>

<script>

import FormLogin from '@/components/FormLogin.vue'

export default {
  name: 'HomeView',
  components: {
    FormLogin
  }
}
</script>
