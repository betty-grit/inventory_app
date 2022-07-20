<template>
  <div class="dash">
    <div class="dashleft">
      <img class="image2" src="@/assets/logo1.svg" alt="" srcset="" />
      <div class="details">
        <div class="cats">
          <img class="image1" src="@/assets/Vector(17).svg" alt="" srcset="" />
          <h2>
            <button>
              <p>Dashboard</p>
            </button>
          </h2>
        </div>
        <div class="cats">
          <img class="image1" src="@/assets/Vector(20).svg" alt="" srcset="" />
          <h2>Inventory</h2>
        </div>
        <div class="cats">
          <img class="image1" src="@/assets/Vector(19).svg" alt="" srcset="" />
          <h2>Categories</h2>
        </div>
        <div class="cats">
          <img class="image1" src="@/assets/Vector(21).svg" alt="" srcset="" />
          <h2>Account Settings</h2>
        </div>
      </div>
      <div class="catss">
        <a href="">Logout</a>
        <img class="image1" src="@/assets/Vector(21).svg" alt="" srcset="" />
      </div>
    </div>
    <div class="dashright">
      <div class="person"><h5>Ammiel Yawson</h5></div>
      <div class="text1"><h4>Overview</h4></div>
      <div class="mainoverview">
        <div class="overview">
          <h3>Products Types</h3>
        </div>
        <div class="overview"><h3>Categories</h3></div>
        <div class="overview"><h3>Sales - July</h3></div>
        <div class="overview"><h3>Inventory Value</h3></div>
      </div>
      <div class="text2"><p>Recently added</p></div>
    </div>
  </div>
</template>
<script>
export default {
  name: "LoginView",
};
</script>
<style scoped>
.person {
  width: 1120px;
  height: 80px;
  left: 0px;
  top: 0px;

  background: #ffffff;
  box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.02);
}
.text1,
.text2 {
  margin-right: 900px;
}
.text2 {
  margin-top: 90px;
}
.image1 {
}
button {
  background-color: #151923;
  border: none;
}
button.hover {
  background-color: #2656d1;
}
h4 {
  font-family: "Overpass";
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 150%;
  /* identical to box height, or 54px */

  letter-spacing: -0.04em;

  color: #1d2128;
}
.overview {
  width: 184px;
  height: 99px;
  margin-right: 10px;
  background: #ffffff;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.04);
  border-radius: 8px;
}
.mainoverview {
  display: flex;
}
.dashright {
  background: #f3f3f3;
}
p {
  left: 0px;
}
.cats {
  display: flex;
  gap: 20px;
  justify-content: center;
}
.cats:hover {
  background-color: #2656d1;
}
.details {
}
.image2 {
  margin-bottom: 104px;
  margin-top: 26px;
  margin-right: 224px;
}
h1 {
}
a {
  font-family: "Lato";
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 150%;
  text-decoration: none;
  color: #ffffff;
}
.catss {
  margin-top: 340px;
  display: flex;
  justify-content: center;
  justify-content: space-around;
}
.dash {
  display: flex;
}
.dashleft {
  width: 320px;
  background-color: #151923;
}
h2 {
  font-family: "Lato";
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 150%;
  color: #ffffff;
  text-align: center;
}
h2:hover {
  background: #2656d1;
  border-radius: 8px;
}
h3 {
  font-family: "Lato";
  font-style: normal;
  font-weight: 400;
  font-size: 16px;
  line-height: 120%;
  /* or 19px */

  color: #595f69;
}
</style>
