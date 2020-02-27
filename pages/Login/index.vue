<template>
  <div class="container">
    <h1>Please login to see the secret content</h1>
    <form>
      <p></p>
      <p>
        <i
          >To login, use <b>demo</b> as username and <b>demo</b> as password.</i
        >
      </p>
      <p>
        Username: <input v-model="formUsername" type="text" name="username" />
      </p>
      <p>
        Password:
        <input v-model="formPassword" type="password" name="password" />
      </p>
      <button type="submit">
        Login
      </button>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {
      formError: null,
      formUsername: '',
      formPassword: ''
    }
  }
  // methods: {
  //   async login() {
  //     try {
  //       await this.$store.dispatch('login', {
  //         username: this.formUsername,
  //         password: this.formPassword
  //       })
  //       this.formUsername = ''
  //       this.formPassword = ''
  //       this.formError = null
  //     } catch (e) {
  //       this.formError = e.message
  //     }
  //   },
  //   async logout() {
  //     try {
  //       await this.$store.dispatch('logout')
  //     } catch (e) {
  //       this.formError = e.message
  //     }
  //   }
  // }
}
</script>

<style>
.container {
  padding: 100px;
}
.error {
  color: red;
}
</style>
