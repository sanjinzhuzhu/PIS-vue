<template>
  <div class="header flex1 colum">
    <!-- 第一行 -->
    <div class="top">
      <div class="top nav flex">
        <div class="top logo container">
        <div class="top logo flex1">logo</div>
        </div>
        <div class="top navlist flex1">People Search</div>
        <div class="top navlist flex1">Phone Lookup</div>
        <div class="top navlist flex1">White Pages</div>
        <div class="top navlist flex1">Address Lookup</div>
        <div class="top navlist flex1">Background Check</div>
      </div>
      <!-- 第二行 -->
      <div class="font">
        People Search and Public Information <br>
        <span>Search Engline</span>
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
.header {
  margin: 0;
  height: 100vh;
  background-color: #eee;
  border: 0.0625em solid black;
}
.flex {
  display: flex;
}
.baise {
  background-color: white;
}
.flex1 {
  flex: 1;
}
.column {
  flex-direction: column;
}
</style>