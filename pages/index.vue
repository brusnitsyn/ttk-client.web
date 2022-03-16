<template>
  <div class="container mx-auto max-w-7xl text-dark">
    <NuxtHeader class="sticky top-0 z-20" />
    <client-only>
      <swiper :options="heroSwiperOptions">

        <swiper-slide>
          <div class="relative">
            <img src="/img/test.jpg" alt="" />
            <div
              class="absolute left-4 bottom-4 max-w-xs md:left-16 md:bottom-14 md:max-w-xl"
            >
              <h1
                class="text-white text-lg md:text-3xl pb-1 font-bold uppercase md:pb-2.5"
              >
                Новое поступление запчастей для техники «АЛМАЗ»
              </h1>
              <a href="" class="text-accent md:text-xl font-semibold"
                >Подробнее</a
              >
            </div>
          </div>
        </swiper-slide>

        <swiper-slide>
          <div class="relative">
            <img src="/img/test.jpg" alt="" />
            <div
              class="absolute left-4 bottom-4 max-w-xs md:left-16 md:bottom-14 md:max-w-xl"
            >
              <h1
                class="text-white text-lg md:text-3xl pb-1 font-bold uppercase md:pb-2.5"
              >
                Новое поступление запчастей для техники «АЛМАЗ»
              </h1>
              <a href="" class="text-accent md:text-xl font-semibold"
                >Подробнее</a
              >
            </div>
          </div>
        </swiper-slide>

        <swiper-slide>
          <div class="relative">
            <img src="/img/test.jpg" alt="" />
            <div
              class="absolute left-4 bottom-4 max-w-xs md:left-16 md:bottom-14 md:max-w-xl"
            >
              <h1
                class="text-white text-lg md:text-3xl pb-1 font-bold uppercase md:pb-2.5"
              >
                Новое поступление запчастей для техники «АЛМАЗ»
              </h1>
              <a href="" class="text-accent md:text-xl font-semibold"
                >Подробнее</a
              >
            </div>
          </div>
        </swiper-slide>

      </swiper>
    </client-only>
    <div class="pt-4 px-4 xl:px-0">
      <h1 class="font-bold text-lg md:text-2xl pb-3">Последние поступления</h1>

      <client-only>
        <swiper :options="actualOrdersSwiperOptions" class="">

          <swiper-slide>
            <div
              class="p-4 border border-[#D3D3D3] hover:bg-accent transition-colors delay-75"
            >
              <a href="">
                <div class="flex flex-col gap-y-8 items-center">
                  <div>
                    <img src="/img/test-item.png" alt="" />
                  </div>
                  <div>
                    <h2 class="font-semibold text-lg leading-5 lg:w-5/6">
                      БЛОК-ШЕСТЕРНЯ КПП МБ АГРО
                    </h2>
                    <h3>42Т.001.01.01.018</h3>
                    <span class="font-medium">12840 ₽</span>
                    <!-- <div class="flex flex-row justify-between">
              <span class="font-medium">12840 ₽</span>
              <a href="" class="text-accent">Перейти</a>
            </div> -->
                  </div>
                </div>
              </a>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div
              class="p-4 border border-[#D3D3D3] hover:bg-accent transition-colors delay-75"
            >
              <a href="">
                <div class="flex flex-col gap-y-8 items-center">
                  <div>
                    <img src="/img/test-item.png" alt="" />
                  </div>
                  <div>
                    <h2 class="font-semibold text-lg leading-5 lg:w-5/6">
                      БЛОК-ШЕСТЕРНЯ КПП МБ АГРО
                    </h2>
                    <h3>42Т.001.01.01.018</h3>
                    <span class="font-medium">12840 ₽</span>
                    <!-- <div class="flex flex-row justify-between">
              <span class="font-medium">12840 ₽</span>
              <a href="" class="text-accent">Перейти</a>
            </div> -->
                  </div>
                </div>
              </a>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div
              class="p-4 border border-[#D3D3D3] hover:bg-accent transition-colors delay-75"
            >
              <a href="">
                <div class="flex flex-col gap-y-8 items-center">
                  <div>
                    <img src="/img/test-item.png" alt="" />
                  </div>
                  <div>
                    <h2 class="font-semibold text-lg leading-5 lg:w-5/6">
                      БЛОК-ШЕСТЕРНЯ КПП МБ АГРО
                    </h2>
                    <h3>42Т.001.01.01.018</h3>
                    <span class="font-medium">12840 ₽</span>
                    <!-- <div class="flex flex-row justify-between">
              <span class="font-medium">12840 ₽</span>
              <a href="" class="text-accent">Перейти</a>
            </div> -->
                  </div>
                </div>
              </a>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div
              class="p-4 border border-[#D3D3D3] hover:bg-accent transition-colors delay-75"
            >
              <a href="">
                <div class="flex flex-col gap-y-8 items-center">
                  <div>
                    <img src="/img/test-item.png" alt="" />
                  </div>
                  <div>
                    <h2 class="font-semibold text-lg leading-5 lg:w-5/6">
                      БЛОК-ШЕСТЕРНЯ КПП МБ АГРО
                    </h2>
                    <h3>42Т.001.01.01.018</h3>
                    <span class="font-medium">12840 ₽</span>
                    <!-- <div class="flex flex-row justify-between">
              <span class="font-medium">12840 ₽</span>
              <a href="" class="text-accent">Перейти</a>
            </div> -->
                  </div>
                </div>
              </a>
            </div>
          </swiper-slide>

          <swiper-slide>
            <div
              class="p-4 border border-[#D3D3D3] hover:bg-accent transition-colors delay-75"
            >
              <a href="">
                <div class="flex flex-col gap-y-8 items-center">
                  <div>
                    <img src="/img/test-item.png" alt="" />
                  </div>
                  <div>
                    <h2 class="font-semibold text-lg leading-5 lg:w-5/6">
                      БЛОК-ШЕСТЕРНЯ КПП МБ АГРО
                    </h2>
                    <h3>42Т.001.01.01.018</h3>
                    <span class="font-medium">12840 ₽</span>
                    <!-- <div class="flex flex-row justify-between">
              <span class="font-medium">12840 ₽</span>
              <a href="" class="text-accent">Перейти</a>
            </div> -->
                  </div>
                </div>
              </a>
            </div>
          </swiper-slide>

        </swiper>
      </client-only>
    </div>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
  data() {
    return {
      heroSwiperOptions: {
        slidesPerView: 1,
        spaceBetween: 16,
        autoplay: {
          delay: 5000,
        },
      },
      actualOrdersSwiperOptions: {
        slidesPerView: 1,
        spaceBetween: 16,
        breakpoints: {
          1280: {
            slidesPerView: 5,
          },
          1024: {
            slidesPerView: 4,
          },
          768: {
            slidesPerView: 3,
          },
          640: {
            slidesPerView: 1,
          },
        },
      },
    };
  },
};
</script>

<style scoped></style>
