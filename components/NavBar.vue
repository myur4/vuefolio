<template>
    <nav class="flex justify-between items-center w-full p-4 lg:p-8 h-20 bg-base-100 fixed">
        <a class="text-4xl font-extrabold text-primary hover:underline" href="#home">George S.</a>

        <div>
            <BurguerMenu v-if="!showBurguer" @click="altMenu()" class="lg:hidden" />
            <div v-if="showBurguer"
                class="flex mt-20 flex-col border-solid w-32 border-secondary rounded-lg border-2 p-2 items-center gap-2 bg-base-100">
                <BurguerMenu @click="altMenu()" class="relative left-10 mb-2 fill-primary" />
                <a class="link-primary hover:underline hover:text-secondary cursor-pointer" href="#about">About Me</a>
                <a class="link-primary hover:underline hover:text-secondary cursor-pointer" href="#skills">Skills</a>
            </div>
        </div>
        <div class="hidden lg:flex gap-3">
            <a class="link-primary lg:text-lg hover:underline hover:text-secondary cursor-pointer" href="#about">About Me</a>
            <a class="link-primary lg:text-lg hover:underline hover:text-secondary cursor-pointer" href="#skills">Skills</a>
        </div>
    </nav>
</template>

<script setup>

let showBurguer = ref(false);

function altMenu() {
    showBurguer.value = !showBurguer.value;
};

</script>
