<script>
  import { register } from "swiper/element/bundle";
  register();
</script>

<swiper-container
  slides-per-view={3}
  space-between={10}
  breakpoints={{
    768: {
      slidesPerView: 4,
    },
  }}
>
  <swiper-slide>Slide 1</swiper-slide>
  <swiper-slide>Slide 2</swiper-slide>
  <swiper-slide>Slide 3</swiper-slide>
</swiper-container>
