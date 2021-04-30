<template>
<div>
    <input type="text" v-model="userId" /> <br />
    <button @click="onLoadUser">Go to user detail page</button>
    <nuxt-child />
  </div>
</template>
<script>


export default {

  data() {
    return {
      userId: ''
    }
  },
  methods: {
    onLoadUser() {
      this.$router.push('/users/' + this.userId);
    }
  }
}
</script>
