<template>
  <div class="w-full min-h-screen flex items-center justify-center px-4 py-10">
    <div class="w-fit flex flex-col items-center gap-5">
      <img src="/images/pre-title.svg" class="w-60 md:w-[300px]" alt="title" />
      <img id="frame" src="/images/cover.png" class="w-[500px] animate-bounce h-fit" alt="title" />
      <img src="/images/name.svg" class="w-80 md:w-[500px] h-fit" alt="title" />
      <div class="flex flex-col w-full md:flex-row items-center gap-4">
        <NuxtLink
          to="/brochure"
          class="flex rounded-md w-full md:px-32 md:w-fit items-center justify-center h-14 md:h-20 md:text-xl bg-white text-[#E7AF3E] hover:bg-white/80"
          >View Brochure</NuxtLink
        >
        <a
          href="https://drive.google.com/uc?export=download&id=1_HJn2MMI4gcTM79ml5xJWvIomVrIbnLT"
          class="w-full md:px-32 md:w-fit flex items-center justify-center h-14 rounded-md text-white font-medium md:h-20 md:text-xl bg-[#E7AF3E] hover:bg-[#E7AF3E]/80"
          >Download Brochure</a
        >
      </div>
      <div class="w-full md:text-xl text-[#E7AF3E] text-center font-normal uppercase mt-10">Forever in our Hearts.</div>
    </div>
  </div>
</template>

<script setup>
const router = useRouter();

onMounted(() => {
  setTimeout(() => {
      const frame = document.getElementById('frame');
      if (frame) {
        frame.classList.remove('animate-bounce');
      }
  }, 3000)
});
</script>
