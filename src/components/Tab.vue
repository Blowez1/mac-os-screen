<template>
  <div class="tab">
    <div class="tab__header">
      <div class="first">
        <div class="buttons">
          <span></span>
          <span></span>
          <span></span>
        </div>

        <libIcon style="margin: 0 30px; cursor: pointer" />

        <div class="arrows">
          <leftArrow />
          <rightArrow class="active" />
        </div>
      </div>

      <div class="search-area">
        <securityIcon style="cursor: pointer" />
        <div class="search-area__input">
          <div>
            <lockIcon />
            <span>apple.com</span>
          </div>
          <reloadIcon class="reload--button" />
        </div>
      </div>

      <div class="tab-nav">
        <exportIcon />
        <plusIcon />
        <windowedIcon />
      </div>
    </div>
    <div class="tab__content">
      <div class="tab__content__box">
        <div class="row">
          <div class="tab__content__box--title">Favorites</div>
          <div class="brands">
            <div class="brands__item">
              <img src="../assets/img/apple.png" alt="" />
              <div class="brands__item__title">Apple</div>
            </div>
            <div class="brands__item">
              <img src="../assets/img/wealthx.png" alt="" />
              <div class="brands__item__title">wealthX</div>
            </div>
            <div class="brands__item">
              <img src="../assets/img/printy.png" alt="" />
              <div class="brands__item__title">Printygram</div>
            </div>
            <div class="brands__item">
              <img src="../assets/img/blm.png" alt="" />
              <div class="brands__item__title">BLM</div>
            </div>
            <div class="brands__item">
              <img src="../assets/img/twitter.png" alt="" />
              <div class="brands__item__title">Twitter</div>
            </div>
            <div class="brands__item">
              <img src="../assets/img/yelp.png" alt="" />
              <div class="brands__item__title">Yelp</div>
            </div>
            <div class="brands__item">
              <img src="../assets/img/dribble.png" alt="" />
              <div class="brands__item__title">Dribble</div>
            </div>
            <div class="brands__item">
              <img src="../assets/img/tesla.png" alt="" />
              <div class="brands__item__title">Tesla</div>
            </div>
            <div class="brands__item">
              <img src="../assets/img/netflix.png" alt="" />
              <div class="brands__item__title">Netflix</div>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="tab__content__box--title">Privacy Report</div>
          <div class="report-alerts">
            <div class="report-alerts__item">
              <reportIcon class="icon" />
              <p>
                In the last seven days Safari has prevented 20 trackers from
                profiling you
              </p>
            </div>
            <div class="report-alerts__item">
              <reportIcon class="icon" />
              <p>
                
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur tortor nunc, aliquam at lacinia eu, ornare nec est.
              </p>
            </div>
            <div class="report-alerts__item">
              <reportIcon class="icon" />
              <p>
                
Donec non erat in mauris eleifend maximus. Phasellus vulputate dolor.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import libIcon from "./icons/libIcon.vue";
import leftArrow from "./icons/leftArrow.vue";
import rightArrow from "./icons/rightArrow.vue";
import securityIcon from "./icons/securityIcon.vue";
import lockIcon from "./icons/lockIcon.vue";
import reloadIcon from "./icons/reloadIcon.vue";
import exportIcon from "./icons/exportIcon.vue";
import plusIcon from "./icons/plusIcon.vue";
import windowedIcon from "./icons/windowedIcon.vue";
import reportIcon from "./icons/reportIcon.vue";

export default {
  name: "Tab",
  components: {
    libIcon,
    leftArrow,
    rightArrow,
    securityIcon,
    lockIcon,
    reloadIcon,
    exportIcon,
    plusIcon,
    windowedIcon,
    reportIcon,
  },
};
</script>