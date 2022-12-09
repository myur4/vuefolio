<template>
    <nav class="flex justify-between items-center w-full px-8 h-28 fixed">
        <h1 class="text-4xl font-extrabold text-primary">George Santos</h1>

        <div>
            <BurguerMenu v-if="!showBurguer"/>
            <div v-if="showBurguer" class="z-50 flex flex-col border-solid w-32 border-secondary rounded-lg border-2 p-4 items-center gap-2">
                <BurguerMenu class="relative left-10 mb-2"/>
                <a class="link-primary">About Me</a>
                <a class="link-primary">Skills</a>
            </div>
        </div>
        <div class="hidden lg:flex gap-3">
            <a class="link-primary">About Me</a>
            <a class="link-primary">Skills & Profeciences</a>
        </div>

    </nav>
</template>

<script setup>

let showBurguer = true;

</script>
