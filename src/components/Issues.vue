<template>
    <h3>Open Issues</h3>

    <h4>Prysm</h4>
    <a href="https://github.com/prysmaticlabs/prysm/issues/12303" target="_blank">Feature: P2P over v4/v6 dual-stack</a>
    <a href="https://github.com/prysmaticlabs/prysm/issues/13436" target="_blank">TestHostIsResolved test fails if running with a public IPv6</a>

    <h4>Lighthouse</h4>
    <a href="https://github.com/sigp/lighthouse/issues/6449" target="_blank" class="closed">Feature: Default --port and --port6 to be identical</a>
    <a href="https://github.com/sigp/lighthouse/issues/4924" target="_blank">IPv6-only node finds no peers</a>

    <h4>Teku</h4>
    <a href="https://github.com/Consensys/teku/issues/8670" target="_blank" class="closed">IPv6 not automatically detected or included in ENR</a>
    <a href="https://github.com/Consensys/teku/issues/8659" target="_blank" class="closed">Feature: Dual-stack works with --p2p-port-ipv6 set to --p2p-port</a>
    <a href="https://github.com/Consensys/teku/issues/10305" target="_blank" class="closed">Feat: Add IPv6 auto-ENR</a>

    <h4>Nimbus (Consensus Layer)</h4>
    <a href="https://github.com/status-im/nimbus-eth2/issues/4839" target="_blank">Feature: IPv6 support</a>
    <a href="https://github.com/status-im/nim-eth/issues/243" target="_blank">IPv6 Support for discv5</a>

    <h4>Grandine</h4>
    <a href="https://github.com/grandinetech/grandine/issues/43" target="_blank">Consider enabling IPv4 / IPv6 dual-stack by default</a>
    <a href="https://github.com/grandinetech/grandine/issues/47" target="_blank">Feature: --libp2p-port and ---libp2p-port-ipv6 identical by default</a>

    <h4>Nethermind</h4>
    <a href="https://github.com/NethermindEth/nethermind/issues/7519" target="_blank" class="closed">Adding --Discovery.DiscV5Enabled true to a synced DB causes Nethermind to fail</a>
    <a href="https://github.com/NethermindEth/nethermind/issues/6822" target="_blank">Enable dual stack IPv6</a>
    <a href="https://github.com/NethermindEth/nethermind/issues/6318" target="_blank">When JsonRpc.EngineHost is a hostname, then it listens only on IPv6, and on ::</a>

    <h4>Geth</h4>
    <a href="https://github.com/ethereum/go-ethereum/issues/23263" target="_blank">Support IPv6 mainnet P2P discovery bootstrap</a>
    <a href="https://github.com/ethereum/go-ethereum/issues/20522" target="_blank">IP address limits might not suitable for IPv6</a>

    <h4>Besu</h4>
    <a href="https://github.com/besu-eth/besu/issues/9874" target="_blank">IPv6 address auto-discovery via DiscV5</a>
    <a href="https://github.com/besu-eth/besu/issues/9810" target="_blank">feat:(docs) - uPNP/NAT with Discovery v5 IPv6 stack is not supported</a>
    <a href="https://github.com/orgs/besu-eth/projects/2" target="_blank">Discovery v5</a>

    <h4>Reth</h4>
    <a href="https://github.com/paradigmxyz/reth/issues/7114" target="_blank" class="closed">Enable dual stack IPv6</a>
    <a href="https://github.com/paradigmxyz/reth/issues/10983" target="_blank" class="closed">IPv6 Only Mode</a>

    <h4>Ethrex</h4>
    <a href="https://github.com/lambdaclass/ethrex/issues/5354" target="_blank">Add support for IPv6 addresses</a>
    <a href="https://github.com/lambdaclass/ethrex/issues/6371" target="_blank">Feat: Dual-stack support (IPv4/IPv6) in discv5</a>

    <h4>Nimbus (Execution Layer)</h4>
    <a href="https://github.com/status-im/nimbus-eth1/issues/2543" target="_blank">Add ipv6 + dual stack support for nimbus</a>
</template>

<style scoped>
@reference "@/assets/main.css";

h4 {
    @apply border-t-1 mt-2 border-zinc-400;
}

a.closed {
    text-decoration-line: underline line-through;
}
</style>
