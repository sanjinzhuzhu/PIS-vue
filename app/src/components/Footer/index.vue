<template>
  <div class="foot container felx">
    <!-- 主区域 -->
    <div class="foot flex1 column">
      <!-- logo栏 -->
      <div class="foot logo flex">logo</div>
      <!-- 内容区 -->
      <div style="margin-top: 1.7rem" class="foot cont">
        <!-- 左区 -->
        <div class="foot left-container flex">
          <!-- 列表区 -->
          <div class="foot menulist flex1 colum">
            <div style="font-weight: 700">MENU</div>
            <div class="foot menulistitem">About</div>
            <div class="foot menulistitem">Portfolio</div>
            <div class="foot menulistitem">Service</div>
            <div class="foot menulistitem">Blog</div>
            <div class="foot menulistitem">Contact</div>
          </div>
          <div>
            <div style="right: 35.125rem" class="foot servelist flex colum">
              <div style="font-weight: 700">SERVE</div>
            </div>
            <div>
              <div class="foot servelistitem">Power & Energy</div>
              <div class="foot servelistitem">Mechanical Works</div>
              <div class="foot servelistitem">Oil and Gas</div>
              <div class="foot servelistitem">Logistics Services</div>
              <div class="foot servelistitem">General Industry</div>
            </div>
          </div>
          <!-- 右区  -->
          <div class="foot right-container flex">
            <!-- 社交软件区 -->
            <div style="margin-right:5rem" class="foot socialcon flex column">
                <div style="font-weight:700"> SOCIAL</div>
             
              <div class="social flex">
                <div class="foot socialcont-bg">
                  <div class="foot socialicon1">1</div>
                </div>
                <div class="foot socialcont-bg">
                  <div class="foot socialicon2">1</div>
                </div>
                <div class="foot socialcont-bg">
                  <div class="foot socialicon3">1</div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="foot btm">
        <div style="margin: 2.5rem" class="foot btm all flex">
          <div class="foot cprt">
            Copyright © 2020 Laaqiq. All Rights Reserved.
          </div>
          <div style="left: 5rem" class="foot foot-Terms">
            <div style="margin-left: 20rem" class="foot-Terms">
              Terms of Use
            </div>
          </div>
          <div class="foot-Privacy">
            <div style="margin-left: 18rem" class="foot-Privacy">
              Privacy Policy
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
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
.foot {
  position: absolute;
  overflow: hidden;
  position: relative;
  /* border: 0.0625em solid black; */
  background-color: #1e1e1e;
  color: #fff;
}

.logo {
  padding: 0;
  width: px;
  height: 48px;
  left: 5rem;
  font-family: "Overpass";
  font-style: normal;
  font-weight: 900;
  font-size: 1.25rem;
  line-height: 3rem;
  display: inline;
}
.menulist {
  left: 14rem;
}

.servelistitem {
  right: 35.125rem;
}
.menulist,
.servelistitem {
  font-weight: 400;
  font-size: 1rem;
  line-height: 2rem;
}
.socialcont-bg {
  background-image: ("~@/assets/images/footer/Oval.png");
}

.cprt {
  color: rgba(255, 255, 255, 0.502972);
  left: 3rem;
}
</style>