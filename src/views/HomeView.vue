<script setup>
import HomeCard from '/src/components/HomeCard.vue'
</script>

<template>
  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Podcasts to make you smarter
    </button>
  </div>

  <div class="py-1.5"></div>

  <div class="flex items-center">
    <HomeCard
      image="https://picsum.photos/id/30/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      image="https://picsum.photos/id/45/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      class="md:block hidden"
      image="https://picsum.photos/id/65/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      class="lg:block hidden"
      image="https://picsum.photos/id/67/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      class="xl:block hidden"
      image="https://picsum.photos/id/100/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
  </div>
  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Recommended radio
    </button>
  </div>

  <div class="py-1.5"></div>

  <div class="flex items-center">
    <HomeCard
      image="https://picsum.photos/id/30/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      image="https://picsum.photos/id/45/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      class="md:block hidden"
      image="https://picsum.photos/id/65/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      class="lg:block hidden"
      image="https://picsum.photos/id/67/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      class="xl:block hidden"
      image="https://picsum.photos/id/100/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
  </div>
  <div class="p-8">
    <button
      type="button"
      class="text-white text-2xl font-semibold hover:underline cursor-pointer"
    >
      Recommended sosngs
    </button>
  </div>

  <div class="py-1.5"></div>

  <div class="flex items-center">
    <HomeCard
      image="https://picsum.photos/id/30/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      image="https://picsum.photos/id/45/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      class="md:block hidden"
      image="https://picsum.photos/id/65/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      class="lg:block hidden"
      image="https://picsum.photos/id/67/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
    <HomeCard
      class="xl:block hidden"
      image="https://picsum.photos/id/100/300/300"
      title="Title is here"
      subTitle="Sub Title is here"
    />
  </div>
</template>
