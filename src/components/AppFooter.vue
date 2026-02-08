<script setup lang="ts">
import LogoIcon from './LogoIcon.vue';

const year = new Date().getFullYear();
</script>

<template>
    <footer class="bg-zinc-900 px-6 py-12">
        <div class="mx-auto max-w-7xl">
            <div
                class="flex flex-col items-start justify-between gap-8 md:flex-row md:items-center"
            >
                <div class="flex items-center gap-2">
                    <LogoIcon class="h-8 w-auto" fill="white" />
                    <span class="text-lg font-semibold text-white"
                        >ShowUp365</span
                    >
                </div>

                <ul class="flex flex-wrap gap-6">
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
                            href="#privacy"
                            class="text-sm text-zinc-400 transition hover:text-white"
                            >Privacy</a
                        >
                    </li>
                    <li>
                        <a
                            href="#terms"
                            class="text-sm text-zinc-400 transition hover:text-white"
                            >Terms</a
                        >
                    </li>
                </ul>
            </div>

            <div class="mt-8 border-t border-zinc-800 pt-8">
                <p class="text-sm text-zinc-500">
                    &copy; {{ year }} ShowUp365. All rights reserved.
                </p>
            </div>
        </div>
    </footer>
</template>
