<template>
  <div class="signup">
    <div class="signupleft">
      <img src="@/assets/logo1.svg" alt="" srcset="" />
      <h1>Sign up</h1>
      <hr />
      <h2>Register now and start managing your inventory like a boss</h2>
      <form>
        <label>Name </label><br />
        <input placeholder="" /><br />
        <label>Email </label><br />
        <input placeholder="" /><br />
        <label>Shop Name </label><br />
        <input placeholder="" /><br />
        <label>Password </label><br />
        <input placeholder="" /><br />
        <label>Password Confirm</label><br />
        <input placeholder="" /><br />
        <button>Sign up</button>
        <h3>
          Already have an account?<span>
            <router-link to="/about"><a>Login</a></router-link>
          </span>
        </h3>
      </form>
    </div>
    <div class="signright">
      <img src="@/assets/Subscriber-bro.svg" alt="" srcset="" />
    </div>
  </div>
</template>
<style scoped>
.signup {
  display: flex;
  width: 100%;
  height: 100vh;
}
.signright {
  background-color: #2656d1;
  width: 75%;
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}
.signupleft {
  width: calc(25%-112px);
  margin: 32px auto;
}
hr {
  width: 23px;
  /* height: 4px; */
  background-color: black;
}
button {
  width: 100%;
  padding: 14px 0px;

  margin-top: 32px;
  background: #2656d1;
  box-shadow: 0px 16px 24px rgba(38, 86, 209, 0.2);
  border-radius: 8px;
  border: none;
}
a {
  text-decoration: none;
  color: blue;
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
}
input {
  width: 100%;
  height: 48px;
  margin-bottom: 20px;
  background: #ffffff;
  border: 1px solid #ced1d9;
  border-radius: 4px;
}
@media only screen and (max-width: 390px) {
  .signright {
    display: none;
  }
}
</style>
