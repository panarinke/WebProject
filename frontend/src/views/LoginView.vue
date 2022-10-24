<template>
  <div class="login-form">
    <h1>Авторизация</h1>
    <hr>
    <LoginVue></LoginVue>
  </div>
</template>

<script>
import LoginVue from "@/components/Login/LoginVue";
export default {
  name: "LoginView",
  components: {LoginVue}
}
</script>

<style scoped>

</style>