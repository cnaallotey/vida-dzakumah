
<template>
    <div class="w-full min-h-screen flex items-center justify-center p-4">
        <div class="w-fit flex flex-col items-center gap-5">
        <img src="/images/pre-title.svg" class="w-[300px]" alt="title">
        <img src="/images/cover.png" class="w-[500px] h-fit" alt="title">
        <img src="/images/name.svg" class="w-[600px] h-fit" alt="title">
        <div class="flex flex-col w-full md:flex-row items-center gap-4">
        <UButton to="/brochure" class=" flex w-full md:px-32 md:w-fit items-center justify-center h-20 text-xl bg-white text-[#E7AF3E] hover:bg-white/80">View Brochure</UButton>
        <a href="/brochure.pdf"  class="w-full md:px-32 md:w-fit flex items-center justify-center rounded-md text-white font-medium h-20 text-xl bg-[#E7AF3E] hover:bg-[#E7AF3E]/80">Download Brochure</a>
        </div>
        </div>
    </div>
</template>

<script setup>
const router = useRouter()
</script>