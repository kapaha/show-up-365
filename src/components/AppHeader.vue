<script setup lang="ts">
import LogoIcon from './LogoIcon.vue';
</script>

<template>
    <header class="bg-zinc-900 px-6 py-4">
        <nav class="mx-auto flex max-w-7xl items-center justify-between">
            <a href="/" class="flex items-center gap-2">
                <LogoIcon class="h-10 w-auto" fill="white" />
                <span class="text-lg font-semibold text-white">ShowUp365</span>
            </a>

            <ul class="hidden items-center gap-8 md:flex">
                <li>
                    <a
                        href="#features"
                        class="text-sm text-zinc-400 transition hover:text-white"
                        >Features</a
                    >
                </li>
                <li>
                    <a
                        href="#about"
                        class="text-sm text-zinc-400 transition hover:text-white"
                        >About</a
                    >
                </li>
                <li>
                    <a
                        href="#download"
                        class="rounded-lg bg-white px-4 py-2 text-sm font-medium text-zinc-900 transition hover:bg-zinc-200"
                        >Get the App</a
                    >
                </li>
            </ul>
        </nav>
    </header>
</template>
