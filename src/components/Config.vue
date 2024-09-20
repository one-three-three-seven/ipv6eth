<template>
    <hr class="h-1 my-4 bg-zinc-500">
    <h3>Dual-Stack Node Configuration</h3>

    <span class="mt-2">Please read the documentation of your client before applying any changes. You might need to adjust settings and open ports in your firewall.</span>

    <h4>Prysm</h4>
    <span class="text-base">Dual-Stack not yet possible</span>
    <!-- <a href="https://docs.prylabs.network/docs/prysm-usage/parameters" target="_blank" class="text-base">Documentation: Command-line options</a> -->

    <h4 class="border-t-2">Lighthouse</h4>
    <a href="https://lighthouse-book.sigmaprime.io/advanced_networking.html#ipv6-support" target="_blank" class="text-base">Documentation: IPv6 support</a>

    <h4 class="border-t-2">Teku</h4>
    <a href="https://docs.teku.consensys.io/how-to/find-and-connect/configure-ipv6" target="_blank" class="text-base">Documentation: Configure IPv6</a>
    <!-- <span class="text-base bg-gray-200">--p2p-interface 0.0.0.0,:: --p2p-advertised-ips IP_V4_ADDRESS,IP_V6_ADDRESS</span> -->

    <h4 class="border-t-2">Nimbus</h4>
    <span class="text-base">Dual-Stack is already the default</span>

    <h4 class="border-t-2">Lodestar</h4>
    <a href="https://chainsafe.github.io/lodestar/run/beacon-management/networking" target="_blank" class="text-base">Documentation: Networking</a>

    <h4 class="border-t-2">Grandine</h4>
    <a href="https://docs.grandine.io/cli_options.html" target="_blank" class="text-base">Documentation: CLI options</a>
</template>

<style scoped>
a {
    @apply link
}

h4 {
    @apply mt-3
}
</style>
