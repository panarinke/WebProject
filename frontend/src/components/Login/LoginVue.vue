<template>
  <form class="login-form">
    <div class="mb-3">
      <label for="exampleInputEmail1" class="form-label">Email адрес</label>
      <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
      <div id="emailHelp" class="form-text">Мы никогда не передадим вашу электронную почту кому-либо еще</div>
    </div>
    <div class="mb-3">
      <label for="exampleInputPassword1" class="form-label">Пароль</label>
      <input type="password" class="form-control" id="exampleInputPassword1">
    </div>
    <div class="mb-3 form-check">
      <input type="checkbox" class="form-check-input" id="exampleCheck1">
      <label class="form-check-label" for="exampleCheck1">Сохранить пароль</label>
    </div>
    <button type="submit" class="btn btn-primary">Войти</button>
  </form>
</template>

<script>
export default {
  name: "LoginVue"
}
</script>

<style scoped>
  .login-form {
    max-width: 400px;
    margin: 25px auto;
    background-color: #f2f2f2;
    padding: 25px;
    margin-top: 200px;
  }

  button.btn.btn-primary {
    color: white;
    background-color: #666666;
    border-color: black;
  }
</style>