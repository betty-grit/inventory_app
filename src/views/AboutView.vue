<template>
  <div class="signup">
    <div class="signupleft">
      <img src="@/assets/logo1.svg" alt="" srcset="" />
      <h1>Login</h1>
      <h2>Sign in to start managing your inventory like a boss.</h2>
      <form>
        <label>Email </label><br />
        <input placeholder="" /><br />

        <input placeholder="" /><br />
        <label>Password </label><br />

        <button>Login</button>
        <h3>
          Already have an account?<span> <a href="">Sign up</a> </span>
        </h3>
      </form>
    </div>
    <div class="signright">
      <img src="@/assets/login.svg" alt="" srcset="" />
    </div>
  </div>
</template>
<script>
export default {
  name: "LoginView",
};
</script>
<style scoped>
.signup {
  display: flex;
  width: calc(100%-112px);
  margin: 0 auto;
}
.signright {
  background: #873ab6;
  margin-left: 56px;
  /* max-width: 469px; */
}
button {
  width: 357px;
  height: 56px;
  left: 0px;
  top: 461px;
  margin-top: 32px;
  background: #873ab6;

  box-shadow: 0px 16px 24px rgba(38, 86, 209, 0.2);
  border-radius: 8px;
  border: none;
}
a {
  text-decoration: none;
}
h1 {
  font-family: "Overpass";
  font-style: normal;
  font-weight: 800;
  font-size: 40px;
  line-height: 130%;
  /* identical to box height, or 52px */

  letter-spacing: -0.06em;

  color: #1d2128;
}
h2 {
  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 150%;
  width: 284px;
  color: #747880;
}
label {
  font-family: "Lato";
  font-style: normal;
  font-weight: 500;
  font-size: 16px;
  line-height: 150%;
  margin-top: 16px;
  color: #3a3f46;
  text-align: left;
}
input {
  width: 357px;
  height: 48px;
  left: 0px;
  top: 114px;
  margin-bottom: 20px;
  background: #ffffff;
  border: 1px solid #ced1d9;
  border-radius: 4px;
}
</style>
