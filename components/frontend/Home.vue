<template>
  <div class="!container mx-auto lg:!px-16 !px-4">
    <Marquee />
    <div class="grid grid-cols-12 gap-2">
      <Tag />
    </div>
    <Heading />
    <Second />
    <Third />
    <Fourth />
    <Fifth />
    <Sixth />
    <Seventh />
    <Eighth />
    <Nineth />
    <Tenth />
  </div>
</template>
<script>
import Marquee from "./widgets/Marquee.vue";
import Tag from "./widgets/Tag.vue";
import Heading from "./section/Heading.vue";
import Second from "./section/Second.vue";
import Third from "./section/Third.vue";
import Fourth from "./section/Fourth.vue";
import Fifth from "./section/Fifth.vue";
import Sixth from "./section/Sixth.vue";
import Seventh from "./section/Seventh.vue";
import Eighth from "./section/Eighth.vue";
import Nineth from "./section/Nineth.vue";
import Tenth from "./section/Tenth.vue";
export default {
  components: {
    Marquee,
    Tag,
    Heading,
    Second,
    Third,
    Fourth,
    Fifth,
    Sixth,
    Seventh,
    Eighth,
    Nineth,
    Tenth,
  },
};
</script>
