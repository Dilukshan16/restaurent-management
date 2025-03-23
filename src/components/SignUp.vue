<template>
  <div class="container">
    <div class="card">
      <img alt="logo" class="logo" src="../assets/resto.png" />
      <h1>Sign Up</h1>
      <form class="form">
        <div class="input">
          <label for="name">Name</label>
          <input type="text" placeholder="Enter your name" />
        </div>

        <div class="input">
          <label for="email">Email</label>
          <input type="email" placeholder="Enter your email" />
        </div>

        <div class="input">
          <label for="password">Password</label>
          <input type="password" placeholder="Enter your password" />
        </div>

        <button type="submit" class="btn">Sign Up</button>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: "SignUp",
};
</script>

<style scoped>
/* Center the container */
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-color: #f8f9fa;
}

/* Card-style form container */
.card {
  background: white;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  text-align: center;
  width: 350px;
}

/* Logo */
.logo {
  width: 100px;
  height: 100px;
  margin-bottom: 1rem;
}

/* Form styles */
.form {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

/* Input fields */
.input {
  display: flex;
  flex-direction: column;
  text-align: left;
}

.input label {
  font-weight: bold;
  margin-bottom: 5px;
}

.input input {
  padding: 10px;
  border: 1px solid #ccc;
  border-radius: 6px;
  font-size: 16px;
}

/* Button */
.btn {
  background-color: #007bff;
  color: white;
  padding: 10px;
  border: none;
  border-radius: 6px;
  font-size: 18px;
  cursor: pointer;
  transition: 0.3s;
}

.btn:hover {
  background-color: #0056b3;
}
</style>
