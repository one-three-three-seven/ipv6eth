<template>
    <div class="flex-1 min-w-80 m-3">
        <ul>
            <li>
                <h3>What is this website about?</h3>
                <span>The current state of IPv6 support within the Ethereum network, why we should improve it, and how we can do it.</span>
            </li>
            <li>
                <h3>Why should we improve the IPv6 support?</h3>
                <span>Not every ISP provides a publicly reachable IPv4 address, or they charge extra fees for it. Sometimes they even require an upgrade to an expensive business plan. Unlike IPv4, IPv6 addresses are typically provided without extra fees.</span>
                <span>It is generally possible to run a node without a public IP address (with outgoing connections only). But the search for peers is slower, you may find fewer and their quality might be worse.</span>
                <span>Making it easier, more reliable, and cheaper to run a node from home is important for increasing the decentralization of the network.</span>
            </li>
            <li>
                <h3>Are there other solutions?</h3>
                <span>Some people enable incoming connections by routing the traffic through a VPN, but this increases the cost and adds another possible single point of failure.</span>
            </li>
            <li>
                <h3>How can we solve this problem?</h3>
                <span>1. The clients need to support IPv6.</span>
                <span>2. We need to increase the number of dual-stack nodes.</span>
                <span>3. The bootnodes should have a dual-stack setup.</span>
                <span>4. All clients should use dual-stack by default.</span>
            </li>
            <li>
                <h3>What is a dual-stack node?</h3>
                <span>A dual-stack node is able to handle IPv4 and IPv6 connections at the same time. They act as bridges between IPv4-only and IPv6-only nodes. Hopefully most of the nodes will be dual-stack in the future.</span>
                <span>Integrating IPv6-only nodes into the P2P network is not doable without dual-stack nodes.</span>
            </li>
            <li>
                <h3>Why do clients not use dual-stack by default?</h3>
                <span>Most clients got the IPv6 support only after the client was already in widespread use. Changing such default settings might be unexpected for the users and could cause issues.</span>
                <span>A slow rollout is definitely safer in case there are any unexpected side effects. However, this is just my opinion. Making it the default setting would speed up the rollout.</span>
            </li>
            <li>
                <h3>Why are no execution layer clients listed?</h3>
                <span>The consensus layer network is more important to keep the node up to the head block.</span>
                <span>Execution layer clients use, by default, the Discv4 protocol to discover other nodes. Discv4 does not allow the advertisement of multiple IP addresses at the same time.
                    Because of this, dual-stack setups are not practical there yet. The execution layer clients first need to use Discv5 by default, before we can think about IPv6 support.</span>
            </li>
            <li>
                <h3>This website contains wrong or outdated information</h3>
                <span>Please open an issue on <a href="https://github.com/one-three-three-seven/ipv6eth" target="_blank">GitHub</a> or ping me on the <a href="https://discord.gg/ethstaker" target="_blank">EthStaker Discord</a>.</span>
            </li>
        </ul>
    </div>
</template>

<style scoped>
ul>li {
    @apply flex flex-col mt-2
}

ul>li>h3 {
    @apply mb-1
}

ul>li>span {
    @apply mb-2
}

a {
    @apply link
}
</style>
