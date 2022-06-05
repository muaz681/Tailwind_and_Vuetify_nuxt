<template>
  <div class="grid grid-cols-12 lg:gap-4 gap-2 lg:px-9 px-0">
    <!-- 1st section -->
    <div class="col-span-12 lg:col-span-3 order-2 lg:order-1">
      <div
        class="grid grid-cols-12 lg:bg-violet-200 bg-transparent lg:p-2 p-0 lg:divide-y lg:divide-zinc-300 divide-transparent"
      >
        <div v-for="n in 3" :key="n" class="col-span-12 lg:px-0 px-1 py-2">
          <SingleListImage />
        </div>
      </div>
      <!-- Ad Section -->
      <SquareAdd />
    </div>
    <!-- 2nd section -->
    <div class="col-span-12 lg:col-span-6 order-1 lg:order-2">
      <div class="grid grid-cols-12 lg:pt-0 pt-2">
        <div class="col-span-12">
          <SinglePostWithSub />
        </div>
      </div>
      <div class="grid grid-cols-12 gap-2">
        <div v-for="n in 2" :key="n" class="col-span-12 lg:col-span-6">
          <SingleListImage />
        </div>
      </div>
    </div>
    <!-- 3rd section -->
    <div class="col-span-12 lg:col-span-3 order-3 lg:order-3">
      <div class="grid grid-cols-12 gap-2">
        <div class="col-span-12">
          <PrayerTime />
          <Decision />
          <SquareAdd />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import SingleListImage from "../widgets/SingleListImage.vue";
import SinglePostWithSub from "../widgets/SinglePostWithSub.vue";
import SquareAdd from "../widgets/SquareAdd.vue";
import PrayerTime from "../widgets/PrayerTime.vue";
import Decision from "../widgets/Decision.vue";
export default {
  components: { SingleListImage, SinglePostWithSub, SquareAdd, PrayerTime, Decision },
};
</script>
