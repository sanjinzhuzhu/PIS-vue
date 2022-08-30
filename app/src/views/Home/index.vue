<template>
  <div class="search flex">
    <div class="search zuxian flex">
      <!-- 搜索悬浮窗盒子-->
      <div class="search father flex">
        <!-- 主体垂直布局-->
        <div class="search son flex column">
          <!-- 第一行 start-here -->
          <div class="search searchtext">
            START HERE - Try searching a friend, relative, celebrity, yourself,
            or someone else you might know…
          </div>
          <!-- 第二行 search item -->
          <div style="color: #929496" class="search itembox-main flex">
            <!-- people单行 -->
            <div
              style="margin-right: 30px padding:0 auto"
              class="search itembox11 flex"
            >
              <img class="search icon-people" :src="peopleIcon" />
              <div style="padding: 0 10px" class="search itemlist">
                People Search
              </div>
            </div>
            <!-- 第二行 2-4 -->
            <img class="search icon-phone" :src="phoneIcon" />
            <div class="search itemlist">Phone Lookup</div>
            <img class="search icon-whitePage" :src="whitePageIcon" />
            <div class="search itemlist">White Pages</div>
            <img class="search icon-address" :src="addressIcon" />
            <div class="search itemlist">Address Lookup</div>
            <img class="search icon-bgcheck" :src="bgcheckIcon" />
            <div class="search itemlist">Background Check</div>
          </div>
          <!-- 第三行 -->
          <div style="align-items: center" class="search searchbox main flex">
            <div
              style="
                border-radius: 10px 0px 0px 10px;
                border-right: 0.0625rem solid #e6e9f0;
                height: 60px;
                line-height: 60px;
              "
              class="search searchitem"
            >
              FIRST NAME
            </div>
            <div
              style="
                border-right: 0.0625rem solid #e6e9f0;
                height: 60px;
                line-height: 60px;
              "
              class="search searchitem"
            >
              LAST NAME
            </div>
            <div
              style="
                border-right: 0.0625rem solid #e6e9f0;
                height: 60px;
                line-height: 60px;
              "
              class="search searchitem"
            >
              CITY
            </div>
            <div class="search search-main flex">
              <div
                style="
                  height: 60px;
                  line-height: 60px;
                  border-radius: 0px 10px 10px 0px;
                  color: #121212;
                "
                class="search searchitem"
              >
                ALL 50 States
                <img
                  style="width: 14px; height: 10px; margin: 0 auto"
                  class="search triangle-icon"
                  :src="triangleIcon"
                />
              </div>
            </div>
            <div
              style="margin: 10px 20px; color: #fff"
              class="search StartSearch flex"
            >
              <div
                style="
                  background-color: #5b77ee;
                  height: 60px;
                  line-height:60px
                  color: #ffff;
                  border-radius: 10px;
                  padding: 0px 10px
                "
                class="search flex"
              >
                <img
                  style="width: 36px; height: 36px; left: 30px; top: 477px"
                  class="search search-icon"
                  :src="searchIcon"
                />
                <div>Start Search</div>
              </div>
            </div>
          </div>

          <!-- 第四行 -->
          <div class="search searchtip">
            Try searching a friend, relative, celebrity, yourself, or someone
            else you might know...
          </div>
          <!-- 第五行 -->
          <div class="search searchsafty main flex">
            <div class="search itembox flex">
              <img
                style="margin: 0 2px; padding: 0 2px"
                class="search icon-lock"
                :src="lockIcon"
              />
              <div class="search icon-font">This connection is secured</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import peopleIcon from "@/assets/images/Search/people.png";
import phoneIcon from "@/assets/images/Search/phone.png";
import whitePageIcon from "@/assets/images/Search/white page.png";
import addressIcon from "@/assets/images/Search/address.png";
import bgcheckIcon from "@/assets/images/Search/bg check.png";
import triangleIcon from "@/assets/images/Search/Polygon 1.png";
import searchIcon from "@/assets/images/Search/search.png";
import lockIcon from "@/assets/images/Search/lock.png";
export default {
  name: "home",
  data() {
    return {
      peopleIcon,
      phoneIcon,
      whitePageIcon,
      addressIcon,
      bgcheckIcon,
      triangleIcon,
      searchIcon,
      lockIcon,
    };
  },
};
</script>

<style scoped>
.felx {
  display: flex;
}
.flex1 {
  flex: 1;
}
* {
  margin: 0;
  padding: 0;
}
/* 
  悬浮窗口开始页
 */
.zuxian,
.father,
.son {
  justify-content: center;
  overflow: hidden;
  position: relative;
  font-family: "Roboto";
  background-color: #ffff;
  box-shadow: 0px 12px 40px rgba(0, 0, 0, 0.05);
  border-radius: 1.25rem;
  margin: -1rem auto 200px;
  display: inline;
  /* padding: 0 40px; */
}
/* 第一行样式 */
.searchtext {
  margin: 1.25rem 2rem 1rem 2.4rem;
  font-style: normal;
  font-weight: 500;
  font-size: 12px;
  line-height: 14px;
  border-radius: 4px;
  /* identical to box height */
  color: #5b77ee;
  background: rgba(91, 119, 238, 0.1);
}
/* 第二行样式 */
.itembox-main {
  align-items: center;
  margin: 30px;
  height: 40px;
  line-height: 40px;
  color: #ffff;
  padding: 0 8px;
}
.itembox11 {
  background-color: #5b77ee;
  border-radius: 8px;
  height: 40px;
  line-height: 38px;
  color: #ffff;
}
.icon-people,
.icon-phone,
.icon-whitePage,
.icon-address,
.icon-bgcheck,
.triangle-icon,
.search-icon,
.icon-lock {
  width: 14px;
  height: 15px;
  margin: 10px;
}
/* 第三行 */
.searchitem {
  align-items: center;
  background: #f4f6fa;
}

.triangle-icon {
  background: url("~@/assets/images/Search/Polygon 1.png");
  background-repeat: no-repeat;
}
.searchitem-icon {
  position: relative;
  background: url("~@/assets/images/Search/search.png");
  background-repeat: no-repeat;
  height: 40px;
  color: #ffff;
  left: 1.875rem;
}
.searchitem {
  font-size: 18px;
  color: rgba(0, 0, 0, 0.4);
  margin: 0, 20px;
  padding: 0 3rem;
  /* margin-top: 40px; */
}
/* 第四行 */
.searchtip {
  margin: 20px 40px;
  line-height: 20px;
  font-size: 12px;
  font-weight: 400px;
}
/* 第五行 */
.icon-lock {
  background: url("~@/assets/images/Search/lock.png");
  background-repeat: no-repeat;
  margin-left: -26.5px;
}
.searchsafty {
  font-size: 12px;
  font-weight: 500px;
  margin: 20px 40px;
}
/* 
悬浮窗口结束页
 */
</style>