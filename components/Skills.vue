<template>
    <section class="wrapper" id="skills" aria-label="skills">
        <div class="flex flex-col gap-2 md:w-1/2">
            <h1
                class="text-4xl text-center md:text-left text-primary font-extrabold underline decoration-secondary">
                Skills & Profeciences</h1>
            <h1 class="text-xl text-info text-center md:text-left font-extrabold">FRAMEWORKS</h1>
            <div>
                <div tabindex="0" class="collapse bg-base-100 rounded-box hover:bg-secondary">
                    <div class="skill-title">
                        <SvgVue/>
                        <h1 class="font-extrabold text-2xl text-primary">Vue.JS</h1>
                        <span class="badge badge-secondary badge-sm">Intermediary</span>
                    </div>
                    <div class="collapse-content">
                        <p class="font-bold text-primary">I've training Vue.JS for the last 3 months, acquiring enough skills to develop pretty
                            websites like that =)
                        </p>
                    </div>
                </div>
            </div>
            <div tabindex="0" class="collapse bg-base-100 rounded-box hover:bg-secondary mx-auto">
                <div class="skill-title">
                    <SvgDotnet/>
                    <h1>.NET</h1>
                    <span class="badge badge-secondary badge-sm">Proficient</span>
                </div>
                <div class="collapse-content">
                    <p class="text-primary font-bold">.NET is my favourite framework for back-end development. I've using it since the launch of Dotnet 6!</p>
                </div>
            </div>
                <div tabindex="0" class="collapse bg-base-100 rounded-box hover:bg-secondary">
                <div class="skill-title">
                    <svg viewBox="0 0 128 128">
                        <path
                            d="M64.004 25.602c-17.067 0-27.73 8.53-32 25.597 6.398-8.531 13.867-11.73 22.398-9.597 4.871 1.214 8.352 4.746 12.207 8.66C72.883 56.629 80.145 64 96.004 64c17.066 0 27.73-8.531 32-25.602-6.399 8.536-13.867 11.735-22.399 9.602-4.87-1.215-8.347-4.746-12.207-8.66-6.27-6.367-13.53-13.738-29.394-13.738zM32.004 64c-17.066 0-27.73 8.531-32 25.602C6.402 81.066 13.87 77.867 22.402 80c4.871 1.215 8.352 4.746 12.207 8.66 6.274 6.367 13.536 13.738 29.395 13.738 17.066 0 27.73-8.53 32-25.597-6.399 8.531-13.867 11.73-22.399 9.597-4.87-1.214-8.347-4.746-12.207-8.66C55.128 71.371 47.868 64 32.004 64zm0 0"
                            fill="#38b2ac"></path>
                    </svg>
                    <h1>Tailwind CSS</h1>
                    <span class="badge badge-secondary badge-sm">Intermediary</span>
                </div>
                <div class="collapse-content">
                    <p class="text-primary font-bold">I've using Tailwind for the past 3 months, and I'm in love with it's simplicity and it's power to make complex UI's!</p>
                </div>
            </div>

            <div>
                <h1 class="text-xl text-info text-center md:text-left font-extrabold">LANGUAGES</h1>
                <div>
                    <div tabindex="0" class="collapse bg-base-100 rounded-box hover:bg-secondary">
                        <div class="skill-title">
                            <SvgTypeScript/>
                            <h1>TypeScript</h1>
                            <span class="badge badge-secondary badge-sm">Intermediary</span>
                        </div>
                        <div class="collapse-content">
                            <p class="text-primary font-bold">I've training Vue.JS for the last 3 months, acquiring enough skills to develop pretty
                                websites like that =)
                            </p>
                        </div>
                    </div>
                </div>
                <div tabindex="0" class="collapse bg-base-100 rounded-box hover:bg-secondary">
                    <div class="skill-title">
                        <SvgCsharp/>
                        <h1>C#</h1>
                        <span class="badge badge-secondary badge-sm">Proficient</span>
                    </div>
                    <div class="collapse-content">
                        <p class="text-primary font-bold">I've mastering C# for months and I don't regret a single second; It's a simple yet powerful language!</p>
                    </div>
                </div>
                <div tabindex="0" class="collapse  bg-base-100 rounded-box hover:bg-secondary">
                    <div class="skill-title">
                        <SvgGopher/>
                        <h1>Golang</h1>
                        <span class="badge badge-secondary badge-sm">Intermediary</span>
                    </div>
                    <div class="collapse-content">
                        <p class="text-primary font-bold">Made more than 3 projects including GoLang for file system manipulation and Discord's api management.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>
</template>

<style lang="postcss" scoped>
.skill-title {
    @apply grid grid-cols-6 justify-center items-center collapse-title text-xl font-medium text-center
}

.skill-title h1 {
    @apply col-span-4 font-extrabold text-xl text-primary
}

</style>