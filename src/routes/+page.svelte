<script lang="ts">
  import { register } from "swiper/element/bundle";
  import "swiper/css";
  import "swiper/css/autoplay";
  import "swiper/css/pagination";
  register();
</script>

<div>
  <swiper-container
    class="container"
    pagination="true"
    pagination-clickable="true"
    pagination-dynamic-bullets="true"
    speed="2000"
    autoplay-delay="1000"
    autoplay-disable-on-interaction="false"
    autoplay-wait-for-transition="true"
    autoplay-pause-on-mouse-enter="true"
    space-between="25"
    slides-per-view="3.2"
    breakpoints={{
      440: { slidesPerView: 1.6 },
      640: { slidesPerView: 1.7 },
      768: { slidesPerView: 2.2 },
      850: { slidesPerView: 2.4 },
      1024: { slidesPerView: 2.7 },
      1280: { slidesPerView: 3.2 },
      1536: { slidesPerView: 3.6 },
    }}
  >
    <swiper-slide class="slide"><div>1</div></swiper-slide>
    <swiper-slide class="slide"><div>2</div></swiper-slide>
    <swiper-slide class="slide"><div>3</div></swiper-slide>
    <swiper-slide class="slide"><div>4</div></swiper-slide>
    <swiper-slide class="slide"><div>5</div></swiper-slide>
    <swiper-slide class="slide"><div>6</div></swiper-slide>
    <swiper-slide class="slide"><div>7</div></swiper-slide>
  </swiper-container>
</div>

<style>
  .slide {
    width: 100%;
    height: 500px;
    background-color: blue;
    color: white;
    font-size: 40px;
    margin-bottom: 30px;
  }

  .slide div {
    margin: 40px;
  }
</style>
