<template>
  <v-container>
    <form action="/login" method="post">
      <div><label>Логин:</label> <input type="text" name="username"/></div>
      <div><label>Пароль:</label> <input type="password" name="password"/> </div>
      <div><input type="submit" value="Вход"/></div>
    </form>
  </v-container>

</template>

<script>
export default {
  name: "login"
}
</script>

<style scoped>

</style>