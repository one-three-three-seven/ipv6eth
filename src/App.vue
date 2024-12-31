<template>
    <h1 class="mx-auto mt-5 text-center">Ethereum IPv6 Support</h1>
    <h4 class="mx-auto mt-1 mb-2 text-center">(Maintained by Sonic)</h4>
    <a href="https://github.com/one-three-three-seven/ipv6eth" class="mx-auto" target="_blank">
        <img src="@/assets/github.svg" width="30" height="30" alt="GitHub">
    </a>
    <div class="flex flex-wrap justify-center">
        <div class="flex-1 flex flex-col min-w-80 m-5 max-w-3xl">
            <Table />
            <hr class="h-0.5 my-4 border-0 bg-zinc-500">
            <Config />
            <hr class="h-0.5 my-4 border-0 bg-zinc-500">
            <Issues />
        </div>
        <FAQ />
    </div>
</template>

<script setup lang="ts">
import Table from '@/components/Table.vue'
import Config from '@/components/Config.vue'
import Issues from '@/components/Issues.vue'
import FAQ from '@/components/FAQ.vue'
</script>

<style>
@reference "@/assets/main.css";

.v-popper__popper .v-popper__inner {
    @apply bg-black
}

.v-popper__popper .v-popper__arrow-outer {
    @apply border-black
}

.v-popper__popper.v-popper__popper--show-from .v-popper__wrapper {
    transform: scale(.5);
}

.v-popper__popper.v-popper__popper--show-to .v-popper__wrapper {
    transform: none;
    transition: transform .2s;
}
</style>
