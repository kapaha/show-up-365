<script setup lang="ts">
import { ref } from 'vue';
import LogoIcon from './LogoIcon.vue';

const baseUrl = import.meta.env.BASE_URL;

const menuOpen = ref(false);
</script>

<template>
    <header class="bg-zinc-900 px-6 py-4">
        <nav class="mx-auto flex max-w-7xl items-center justify-between">
            <a :href="baseUrl" class="flex items-center gap-2">
                <LogoIcon class="h-10 w-auto" fill="white" />
                <span class="xs:block hidden text-lg font-semibold text-white"
                    >ShowUp365</span
                >
            </a>

            <div class="flex items-center gap-4 md:hidden">
                <a
                    href="#download"
                    class="rounded-lg bg-white px-4 py-2 text-center text-sm font-medium text-zinc-900 transition hover:bg-zinc-200"
                    >Get the App</a
                >
                <button
                    type="button"
                    class="text-zinc-400 transition hover:text-white"
                    aria-label="Toggle menu"
                    @click="menuOpen = !menuOpen"
                >
                    <svg
                        v-if="!menuOpen"
                        class="h-6 w-6"
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                        stroke-width="2"
                    >
                        <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M4 6h16M4 12h16M4 18h16"
                        />
                    </svg>
                    <svg
                        v-else
                        class="h-6 w-6"
                        fill="none"
                        viewBox="0 0 24 24"
                        stroke="currentColor"
                        stroke-width="2"
                    >
                        <path
                            stroke-linecap="round"
                            stroke-linejoin="round"
                            d="M6 18L18 6M6 6l12 12"
                        />
                    </svg>
                </button>
            </div>

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
                        class="rounded-lg bg-white px-4 py-2 text-center text-sm font-medium text-zinc-900 transition hover:bg-zinc-200"
                        >Get the App</a
                    >
                </li>
            </ul>
        </nav>

        <ul
            v-if="menuOpen"
            class="mx-auto mt-4 flex max-w-7xl flex-col gap-4 border-t border-zinc-800 pt-4 md:hidden"
        >
            <li>
                <a
                    href="#features"
                    class="block text-sm text-zinc-400 transition hover:text-white"
                    @click="menuOpen = false"
                    >Features</a
                >
            </li>
            <li>
                <a
                    href="#about"
                    class="block text-sm text-zinc-400 transition hover:text-white"
                    @click="menuOpen = false"
                    >About</a
                >
            </li>
        </ul>
    </header>
</template>
