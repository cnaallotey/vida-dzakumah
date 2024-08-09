<template>
    <div class="w-full">
        <div class="max-w-screen-lg mx-auto px-4 py-5">
        <img v-for="i in 30" :src="`/images/doc/page${i}.jpg`" class="w-fit" :alt="`page ${i}`">
        </div>
    </div>
</template>