<script setup lang="ts">
import LogoIcon from '../components/LogoIcon.vue';
</script>

<template>
    <!-- Hero -->
    <section class="bg-zinc-950 px-6 py-24 md:py-32">
        <div class="mx-auto max-w-3xl text-center">
            <LogoIcon class="mx-auto mb-8 h-20 w-auto" fill="white" />
            <h1 class="text-4xl font-bold tracking-tight text-white md:text-6xl">
                Show up every day.
                <br />
                <span class="text-zinc-400">See the proof.</span>
            </h1>
            <p class="mx-auto mt-6 max-w-xl text-lg text-zinc-400">
                A dead-simple habit tracker that shows your entire year at a glance. One goal.
                365 dots. Green when you show up, red when you don't.
            </p>
            <div class="mt-10 flex flex-col items-center justify-center gap-4 sm:flex-row">
                <a
                    href="#download"
                    class="rounded-xl bg-white px-8 py-3 text-sm font-semibold text-zinc-900 transition hover:bg-zinc-200"
                    >Download for iOS</a
                >
                <a
                    href="#how-it-works"
                    class="text-sm font-medium text-zinc-400 transition hover:text-white"
                    >See how it works &darr;</a
                >
            </div>
        </div>
    </section>

    <!-- How it works -->
    <section id="how-it-works" class="bg-white px-6 py-20">
        <div class="mx-auto max-w-4xl">
            <h2 class="text-center text-2xl font-bold text-zinc-900 md:text-3xl">
                Three taps. That's it.
            </h2>
            <div class="mt-14 grid gap-10 md:grid-cols-3">
                <div class="text-center">
                    <div
                        class="mx-auto flex h-12 w-12 items-center justify-center rounded-full bg-zinc-900 text-xl font-bold text-white"
                    >
                        1
                    </div>
                    <h3 class="mt-4 text-lg font-semibold text-zinc-900">Set your goal</h3>
                    <p class="mt-2 text-sm text-zinc-500">
                        Pick the one thing you want to do every single day. Exercise, read, code,
                        meditate &mdash; whatever matters to you.
                    </p>
                </div>
                <div class="text-center">
                    <div
                        class="mx-auto flex h-12 w-12 items-center justify-center rounded-full bg-zinc-900 text-xl font-bold text-white"
                    >
                        2
                    </div>
                    <h3 class="mt-4 text-lg font-semibold text-zinc-900">Mark your day</h3>
                    <p class="mt-2 text-sm text-zinc-500">
                        Did you show up? Tap green. Didn't make it? Tap red and optionally log why.
                        It takes two seconds.
                    </p>
                </div>
                <div class="text-center">
                    <div
                        class="mx-auto flex h-12 w-12 items-center justify-center rounded-full bg-zinc-900 text-xl font-bold text-white"
                    >
                        3
                    </div>
                    <h3 class="mt-4 text-lg font-semibold text-zinc-900">See your year</h3>
                    <p class="mt-2 text-sm text-zinc-500">
                        Watch 365 dots fill with colour. Your entire year of effort, visible at a
                        glance. No charts, no streaks &mdash; just the truth.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Features -->
    <section id="features" class="bg-zinc-950 px-6 py-20">
        <div class="mx-auto max-w-4xl">
            <h2 class="text-center text-2xl font-bold text-white md:text-3xl">
                Built for accountability, not complexity
            </h2>
            <div class="mt-14 grid gap-8 md:grid-cols-2">
                <div class="rounded-xl bg-zinc-800/50 p-6">
                    <h3 class="text-lg font-semibold text-white">Year at a glance</h3>
                    <p class="mt-2 text-sm text-zinc-400">
                        365 dots on one screen. Green for days you showed up, red for days you
                        didn't. Instantly see how consistent you've been.
                    </p>
                </div>
                <div class="rounded-xl bg-zinc-800/50 p-6">
                    <h3 class="text-lg font-semibold text-white">Know why you miss</h3>
                    <p class="mt-2 text-sm text-zinc-400">
                        Log a note when you skip a day. The app spots patterns &mdash; are you
                        always missing because of work? Fatigue? Travel? Now you know.
                    </p>
                </div>
                <div class="rounded-xl bg-zinc-800/50 p-6">
                    <h3 class="text-lg font-semibold text-white">Monthly drill-down</h3>
                    <p class="mt-2 text-sm text-zinc-400">
                        Switch to the calendar view for a closer look at any month. See completion
                        rates and showed-up percentages.
                    </p>
                </div>
                <div class="rounded-xl bg-zinc-800/50 p-6">
                    <h3 class="text-lg font-semibold text-white">Make it yours</h3>
                    <p class="mt-2 text-sm text-zinc-400">
                        Choose from 12 background themes or use your own photo. Your tracker should
                        feel like yours.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- About / Philosophy -->
    <section id="about" class="bg-white px-6 py-20">
        <div class="mx-auto max-w-2xl text-center">
            <h2 class="text-2xl font-bold text-zinc-900 md:text-3xl">
                Most habit apps do too much
            </h2>
            <p class="mt-6 text-zinc-500">
                You don't need 14 habits, weekly reports, and social feeds. You need one question
                answered honestly every day: <strong class="text-zinc-900">did I show up?</strong>
            </p>
            <p class="mt-4 text-zinc-500">
                ShowUp365 tracks a single daily goal with a visual calendar that makes your
                consistency impossible to ignore. No gamification, no streaks to protect, no guilt
                trips. Just an honest record of the year.
            </p>
        </div>
    </section>

    <!-- CTA -->
    <section id="download" class="bg-zinc-950 px-6 py-20">
        <div class="mx-auto max-w-2xl text-center">
            <h2 class="text-2xl font-bold text-white md:text-3xl">Start showing up</h2>
            <p class="mt-4 text-zinc-400">
                Free to download. No account required. Your data stays on your device.
            </p>
            <div class="mt-8">
                <a
                    href="#"
                    class="inline-block rounded-xl bg-white px-8 py-3 text-sm font-semibold text-zinc-900 transition hover:bg-zinc-200"
                    >Download for iOS</a
                >
            </div>
        </div>
    </section>
</template>
