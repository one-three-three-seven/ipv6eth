<template>
    <h3>Open Issues</h3>

    <h4>Prysm</h4>
    <a href="https://github.com/prysmaticlabs/prysm/issues/12303" target="_blank" class="text-base">Feature: P2P over v4/v6 dual-stack</a>

    <h4>Lighthouse</h4>
    <a href="https://github.com/sigp/lighthouse/issues/6449" target="_blank" class="text-base">Feature: Default --port and --port6 to be identical</a>
    <a href="https://github.com/sigp/lighthouse/issues/4924" target="_blank" class="text-base">IPv6-only node finds no peers</a>

    <h4>Teku</h4>
    <a href="https://github.com/Consensys/teku/issues/8670" target="_blank" class="text-base">IPv6 not automatically detected or included in ENR</a>
    <a href="https://github.com/Consensys/teku/issues/8659" target="_blank" class="text-base">Feature: Dual-stack works with --p2p-port-ipv6 set to --p2p-port</a>

    <h4>Nimbus</h4>
    <a href="https://github.com/status-im/nimbus-eth2/issues/6591" target="_blank" class="text-base">Public ip6 not shown in last_seen_p2p_address of Nimbus peer; nor in p2p_addresses of node identity</a>
    <a href="https://github.com/status-im/nimbus-eth2/issues/4839" target="_blank" class="text-base">Feature: IPv6 support</a>

    <h4>Lodestar</h4>
    <a href="https://github.com/ChainSafe/lodestar/issues/6532" target="_blank" class="text-base">Unused p2p_addresses & missing ipv6 address in disvoery_addresses in identity fields</a>
    <a href="https://github.com/ChainSafe/lodestar/issues/7123" target="_blank" class="text-base">Dual-stack adds tcp to discovery-addresses, does not list ip4</a>
    <a href="https://github.com/ChainSafe/lodestar/issues/6531" target="_blank" class="text-base">bug: uncaughtException: Configured bind multiaddrs must have different ports</a>

    <h4>Grandine</h4>
    <a href="https://github.com/grandinetech/grandine/issues/43" target="_blank" class="text-base">Consider enabling IPv4 / IPv6 dual-stack by default</a>
    <a href="https://github.com/grandinetech/grandine/issues/47" target="_blank" class="text-base">Feature: --libp2p-port and ---libp2p-port-ipv6 identical by default</a>

    <h4>Nethermind</h4>
    <a href="https://github.com/NethermindEth/nethermind/issues/7519" target="_blank" class="text-base">Adding --Discovery.DiscV5Enabled true to a synced DB causes Nethermind to fail</a>
    <a href="https://github.com/NethermindEth/nethermind/issues/6822" target="_blank" class="text-base">Enable dual stack IPv6</a>

    <h4>Geth</h4>
    <a href="https://github.com/ethereum/go-ethereum/issues/23263" target="_blank" class="text-base">Support IPv6 mainnet P2P discovery bootstrap</a>
    <a href="https://github.com/ethereum/go-ethereum/issues/20522" target="_blank" class="text-base">IP address limits might not suitable for IPv6</a>

    <h4>Besu</h4>
    <a href="https://github.com/hyperledger/besu/issues/3600" target="_blank" class="text-base">Validate enabling ipv6 improves syncing</a>

    <h4>Reth</h4>
    <a href="https://github.com/paradigmxyz/reth/issues/7114" target="_blank" class="text-base">Enable dual stack IPv6</a>
    <a href="https://github.com/paradigmxyz/reth/issues/10983" target="_blank" class="text-base">IPv6 Only Mode</a>
</template>

<style scoped>
h4 {
    @apply border-t-2 mt-2
}
</style>
