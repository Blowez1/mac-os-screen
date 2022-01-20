<template>
  <header>
    <div class="nav-container">
        <ul class="nav">
          <li><appleIcon class="icon" /></li>
          <li>Safari</li>
          <li>File</li>
          <li>Edit</li>
          <li>View</li>
          <li>History</li>
          <li>Bookmarks</li>
          <li>Window</li>
          <li>Help</li>
        </ul>
    </div>
    <div class="nav-container">
        <ul class="nav">
          <li><batteryIcon class="icon" /></li>
          <li><wifiIcon class="icon" /></li>
          <li><searchIcon class="icon" /></li>
          <li><switchIcon class="icon" /></li>
        </ul>
        <span class="date">Mon Jun 22 9:41 AM</span>
    </div>
  </header>
</template>
<script>
import appleIcon from "./icons/appleIcon.vue";
import batteryIcon from "./icons/batteryIcon.vue";
import searchIcon from "./icons/searchIcon.vue";
import switchIcon from "./icons/switchIcon.vue";
import wifiIcon from "./icons/wifiIcon.vue";

export default {
  name: "Header",
  components: {
    appleIcon,
    batteryIcon,
    searchIcon,
    switchIcon,
    wifiIcon,
  },
};
</script>