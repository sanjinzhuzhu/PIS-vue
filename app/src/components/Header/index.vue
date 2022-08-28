<template>
  <div class="header flex1 colum">
    <div class="header-mask">
      <!-- 第一行 -->
      <div class="top flex1">
        <div class="top nav flex">
          <div class="top logo flex container">
            <div class="top logo flex1">logo</div>
          </div>
          <div style="margin-right:-11rem" class="top navlist flex1">People Search</div>
          <div style="margin-right:-12rem" class="top navlist flex1">Phone Lookup</div>
          <div style="margin-right:-10rem" class="top navlist flex1">White Pages</div>
          <div style="margin-right:-9rem" class="top navlist flex1">Address Lookup</div>
          <div  class="top navlist flex1">Background Check</div>
        </div>
        <!-- 第二行 -->
        <div class="font">
          People Search and Public Information <br />
          <span>Search Engline</span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
.flex {
  display: flex;
}
.flex1 {
  flex: 1;
}
.column {
  flex-direction: column;
}
.header {
  position: relative;
  border: 0.0625em solid black;
  background: url("~@/components/Header/images/Mask Group.png"),
    linear-gradient(
      180deg,
      rgba(71, 73, 160, 0.6) -5.19%,
      rgba(45, 63, 142, 0.95) 100%
    );
}
.header-mask {
  background: url("~@/components/Header/images/Rectangle 10.png");
  padding: 0.625rem 5rem;
}
.header > div {
  color: #fff;
}
.logo {
  width: 48px;
  height: 28px;

  font-family: "Roboto";
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 28px;
}
.navlist {
  margin: auto;
  width: 128px;
  height: 23px;
  text-align: right;
  font-family: "Roboto";
  font-style: normal;
  font-weight: 400;
  font-size: 1.25rem;
  line-height: 1.465rem;
}
.font {
  font-style: normal;
  margin: 5rem auto auto;
  font-weight: 900;
  font-size: 3.75rem;
  line-height: 4.375rem;
  text-align: center;
  height: 140px;
  left: 447px;
  top: 152px;
}
</style>