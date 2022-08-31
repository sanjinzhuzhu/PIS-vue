<template>
  <!-- search 模块开始 -->
  <div class="home flex column">
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
              <img
                style="margin: 10px 7px"
                class="search icon-people"
                :src="peopleIcon"
              />
              <div style="width: 120px" class="search itemlist">
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
                margin-left: 38px;
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
                <div style="width: 100px">Start Search</div>
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
    <!-- search 模块结束 -->

    <!-- what cocoIcon -->
    <div
      style="
        font-weight: 900;
        font-size: 36px;
        line-height: 42px;
        text-align: center;
      "
      class="what what-coco"
    >
      What Can I Find on CocoFinder?
    </div>

    <div class="coco-bigcontainer">
      <!-- 第一排 -->
      <div class="coco flex">
        <div class="icon-container flex column">
          <div style="background: #6fb4f91a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-phone"
              :src="cocoPhoneIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Phone Number Identity</div>
          </div>
        </div>
        <div class="icon-container flex column">
          <div style="background: #6fcf8c1a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-greenery"
              :src="cocoGreeneryIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Age and Date of Birth</div>
          </div>
        </div>
        <div class="icon-container flex column">
          <div style="background: #65ced51a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-file"
              :src="cocoFileIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Background Check</div>
          </div>
        </div>
      </div>
      <!-- 第二排 -->
      <div class="coco flex">
        <div class="icon-container flex column">
          <div style="background: #62be4b1a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-chuizi"
              :src="cocoChuiziIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Court Records</div>
          </div>
        </div>
        <div class="icon-container flex column">
          <div style="background: #3682d21a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-people"
              :src="cocoPeopleIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Relatives</div>
          </div>
        </div>
        <div class="icon-container flex column">
          <div style="background: #72e4a91a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-tel"
              :src="cocoTelIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Contact Numbers</div>
          </div>
        </div>
      </div>
      <!-- 第三排 -->
      <div class="coco flex">
        <div class="icon-container flex column">
          <div syle="background: #68ADF91A;" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-house"
              :src="cocoHouseIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Current Address</div>
          </div>
        </div>
        <div class="icon-container flex column">
          <div style="background: #8952ec1a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-car"
              :src="cocoCarIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Traffic Tickets</div>
          </div>
        </div>
        <div class="icon-container flex column">
          <div style="background: #e582421a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-portfolio"
              :src="cocoPortfolioIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Sex Offender Data</div>
          </div>
        </div>
      </div>
      <!-- 第四排 -->
      <div class="coco flex">
        <div class="icon-container flex column">
          <div style="background: #efa2621a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-handcuffs"
              :src="cocohandcuffsIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Arrest Records</div>
          </div>
        </div>
        <div class="icon-container flex column">
          <div style="background: #3682d21a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-box"
              :src="cocoBoxIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Vital Records</div>
          </div>
        </div>
        <div class="icon-container flex column">
          <div style="background: #efa2621a" class="bgicon flex">
            <img
              style="width: 15px; height: 30px; margin: 10px auto"
              class="coco-crfile"
              :src="cocoCrfileIcon"
            />
          </div>
          <div class="what container-font">
            <div class="coco-font">Criminal Records</div>
          </div>
        </div>
      </div>
    </div>
    <!-- how cocoIcon -->
    <div class="how how-coco">
      <div
        style="
          font-weight: 900;
          font-size: 36px;
          line-height: 42px;
          text-align: center;
          margin-top: 90px;
        "
        class="what how-coco"
      >
        How Can I Use CocoFinder?
      </div>

      <div class="coco-bigbgcontainer">
        <div class="coco-bg flex column">
          <img style="margin:0 auto" class="coco people-search" :src="peopleSearchIcon" />
          <div style="margin:20px auto ;font-size:20px" class="people-search">People Search</div>
          <div style="margin:0 auto; padding:20px ;font-size:8px ;justfy-content:center" class="people-context">
            Finding people by searching for them through their name. People finder tool to find family members, friends,acquaintances, dates,and more.
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
import cocoPhoneIcon from "@/assets/images/coco/phone.png";
import cocoGreeneryIcon from "@/assets/images/coco/greenery.png";
import cocoFileIcon from "@/assets/images/coco/file.png";
import cocoChuiziIcon from "@/assets/images/coco/chuizi.png";
import cocoPeopleIcon from "@/assets/images/coco/people.png";
import cocoTelIcon from "@/assets/images/coco/tel.png";
import cocoHouseIcon from "@/assets/images/coco/house.png";
import cocoCarIcon from "@/assets/images/coco/car.png";
import cocoPortfolioIcon from "@/assets/images/coco/portfolio.png";
import cocohandcuffsIcon from "@/assets/images/coco/portfolio.png";
import cocoBoxIcon from "@/assets/images/coco/box.png";
import cocoCrfileIcon from "@/assets/images/coco/crfile.png";
import peopleSearchIcon from "@/assets/images/coco/people-search.png"

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
      cocoPhoneIcon,
      cocoGreeneryIcon,
      cocoFileIcon,
      cocoChuiziIcon,
      cocoPeopleIcon,
      cocoTelIcon,
      cocoHouseIcon,
      cocoCarIcon,
      cocoPortfolioIcon,
      cocohandcuffsIcon,
      cocoBoxIcon,
      cocoCrfileIcon,
      peopleSearchIcon,
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
  margin: -15rem auto 180px;
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

/* waht coco */
.what {
  font-family: "Roboto";
  font-style: normal;
  color: #0e2e63;
  margin-bottom: 80px;
}
.coco-bigcontainer {
  margin: 0px auto;
}
.icon-container {
  height: 40px;
  width: 230px;
  background: #ffffff;
  box-shadow: 0px 8px 30px rgba(0, 0, 0, 0.05);
  margin: 10px 50px;
}
.bgicon {
  /* position: relative; */
  height: 40px;
  width: 40px;
  /* background: #6FB4F91A; */
}
.coco-font {
  /* position: absolute; */
  font-size: 10px;
  font-weight: 500;
  margin: -27px 49px;
}
.how-coco {
 align-items: center;
  margin-top: 80px;

  background: #f4f6fa;
}
.coco-bigbgcontainer {
  width: 300px;
  height: 200px;
  background-color: #ffffff;
  color: #204178;
  border-radius: 12px;
  margin: 0 auto;

 
}
</style>