<template>
  <div class="search flex">
    <div class="search zuxian flex">
      <!-- 搜索悬浮窗盒子-->
      <div class="search father flex">
        <!-- 总体垂直布局-->
        <div class="search son flex column">
          <!-- 第一行 start-here -->
          <div class="search searchtext">
            START HERE - Try searching a friend, relative, celebrity, yourself,
            or someone else you might know…
          </div>
          <!-- 第二行 search item -->
          <div class="search itembox-main flex">
            <div class="search itembox flex">
              <div class="search">icon</div>
              <div class="search itemlist">People Search</div>
            </div>
            <div class="search itembox flex">
              <div class="search">icon</div>
              <div class="search itemlist">Phone Lookup</div>
            </div>
            <div class="search itembox flex">
              <div class="search search-icon"></div>
              <div class="search itemlist">White Pages</div>
            </div>
            <div class="search itembox flex">
              <div class="search search-icon"></div>
              <div class="search itemlist">Address Lookup</div>
            </div>
            <div style="margin-right:5rem" class="search itembox flex">
              <div class="search search-icon"></div>
              <div class="search itemlist">Background Check</div>
            </div>
          </div>
          <!-- 第三行 -->
          <div class="search searchbox main flex">
            <div class="search searchitem">FIRST NAME</div>
            <div class="search searchitem">LAST NAME</div>
            <div class="search searchitem">CITY</div>
            <div class="search searchite main flex">
              <div class="search searchitem">ALL 50 States</div>
              <div class="search searchitem search-icon"></div>
            </div>
            <div class="search searchite main flex">
              <div class="search icon-bg">
                <div class="search icon">icon</div>
              </div>
              <div class="search searchitem">Start Search</div>
            </div>
          </div>
          <!-- 第四行 -->
          <div class="search searchtip main flex">
            <div class="search tipbox">
              Try searching a friend, relative, celebrity, yourself, or someone
              else you might know...
            </div>
          </div>
          <!-- 第五行 -->
          <div class="search searchsafty main flex">
            <div class="search itembox flex">
              <div class="search icon-img">icon</div>
              <div class="search icon-font">This connection is secured</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "home",
};
</script>

<style>
.felx {
  display: flex;
}
.flex1 {
  flex: 1;
}
.search {
  border: 0.0625rem solid black;
}
.zuxian,
.father,
.son {
  position: relative;
  border-radius: 15px;
  background-color: #ffff;
  margin: -10px auto;
  display: inline;
}
/* 第一行样式 */
.searchtext {
  font-family: "Roboto";
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 14px;
  /* identical to box height */
  color: #5b77ee;
  background: rgba(91, 119, 238, 0.1);
  border-radius: 4px;
}
/* 第二行样式 */
.itembox-main {
  justify-content: center;
  align-items: center;
  padding: 8px 12px;
  gap: 8px;
  height: 40px;
}
</style>