<template>
  <div class="login-container">
    <form>
      <div class="input-group">
        <label for="username">Username</label>
        <input id="username" type="text" placeholder="Enter your username" />
      </div>
      <div class="input-group">
        <label for="password">Password</label>
        <input id="password" type="password" placeholder="Enter your password" />
        <button type="button">Show/Hide Password</button>
      </div>
      <button type="submit">Login</button>
    </form>
  </div>
</template>

<script>
export default {
  data() {
    return {};
  }
};
</script>

<style scoped>
.login-container {
  max-width: 400px;
  margin: 0 auto;
  padding: 20px;
  background-color: #f4f4f4;
  border-radius: 8px;
}

.input-group {
  margin-bottom: 15px;
}

.input-group label {
  display: block;
  margin-bottom: 5px;
}

.input-group input {
  width: 100%;
  padding: 10px;
  border-radius: 4px;
  border: 1px solid #ccc;
}

button {
  width: 100%;
  padding: 10px;
  border-radius: 4px;
  border: none;
  background-color: #007bff;
  color: white;
  cursor: pointer;
}

button[type="button"] {
  background-color: #28a745;
  width: auto;
  margin-top: 10px;
}
</style>

