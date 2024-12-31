<template>
    <h3>Dual-Stack Node Configuration</h3>

    <span class="mt-2">Please read the documentation of your client before applying any changes. You might need to adjust settings and open ports in your firewall.</span>

    <h4>Prysm</h4>
    <span class="text-base">Dual-Stack not yet possible</span>

    <h4>Lighthouse</h4>
    <a href="https://lighthouse-book.sigmaprime.io/advanced_networking.html#ipv6-support" target="_blank">Documentation: IPv6 support</a>

    <h4>Teku</h4>
    <a href="https://docs.teku.consensys.io/how-to/find-and-connect/configure-ipv6" target="_blank">Documentation: Configure IPv6</a>

    <h4>Nimbus</h4>
    <span class="text-base">Dual-Stack is already the default</span>

    <h4>Lodestar</h4>
    <a href="https://chainsafe.github.io/lodestar/run/beacon-management/networking" target="_blank">Documentation: Networking</a>

    <h4>Grandine</h4>
    <a href="https://docs.grandine.io/cli_options.html" target="_blank">Documentation: CLI options</a>
</template>

<style scoped>
@reference "@/assets/main.css";

h4 {
    @apply border-t-1 mt-2 border-zinc-400
}
</style>
