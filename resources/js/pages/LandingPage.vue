<script setup lang="ts">
import { Head } from '@inertiajs/vue3';
</script>

<template>
    <Head title="To Do List | Tugas Magang Laravel ">
        <link rel="preconnect" href="https://rsms.me/" />
        <link rel="stylesheet" href="https://rsms.me/inter/inter.css" />
    </Head>
    <div class="flex h-screen flex-col items-center justify-center bg-[url(/resources/images/landing-page.png)] bg-cover bg-center bg-no-repeat">
        <div class="flex flex-col items-center gap-8 p-8">
            <div class="flex flex-col items-center gap-6">
                <h1 class="text-center font-[Manrope] text-7xl leading-20 font-medium tracking-[-3px]">
                    Aplikasi To-do List Laravel <br />
                    <span class="font-[Instrument-Serif] font-normal text-neutral-600 italic"> Simpel, Cepat, dan Efisien </span>
                </h1>
                <p class="max-w-2xl text-center font-[Inter] text-xl text-[#0000006a]">
                    Tugas menumpuk? Deadline menanti? Saatnya kamu punya alat bantu yang bikin hidup lebih teratur.
                </p>
            </div>
            <div class="flex flex-col items-center">
                <button class="rounded-full bg-primary px-5 py-3 text-xl font-normal text-white shadow-md">Coba Sekarang!</button>
            </div>
        </div>
    </div>
</template>
