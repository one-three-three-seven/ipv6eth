<template>
    <h3 class="text-center mb-2">Consensus Layer</h3>
    <div class="overflow-x-auto">
        <table class="w-full">
            <thead>
                <tr>
                    <th></th>
                    <th>Prysm</th>
                    <th>Lighthouse</th>
                    <th>Teku</th>
                    <th>Nimbus</th>
                    <th>Lodestar</th>
                    <th>Grandine</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>IPv6 Support</td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                </tr>
                <tr>
                    <td>Dual-Stack Support</td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                </tr>
                <tr>
                    <td>Dual-Stack by Default</td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                </tr>
                <tr>
                    <td>Manual Dual-Stack ENR</td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                </tr>
                <tr>
                    <td>Auto Dual-Stack ENR</td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <InformationCircleIcon class="orange-icon" v-tooltip="{ content: 'The IPv6 address was not automatically detected', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                    <td>
                        <InformationCircleIcon class="orange-icon" v-tooltip="{ content: 'The IPv6 address was not automatically detected', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                    <td>
                        <InformationCircleIcon class="orange-icon" v-tooltip="{ content: 'The IPv6 address was not automatically detected', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                    <td>
                        <InformationCircleIcon class="orange-icon" v-tooltip="{ content: 'The IPv6 address was not automatically detected', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                </tr>
                <tr>
                    <td>Dual-Stack Bootnodes</td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                </tr>
                <tr>
                    <td>IPv4/IPv6 Same Port #</td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                </tr>
                <tr>
                    <td>Developer Feedback</td>
                    <td>
                        <!-- Placeholder -->
                    </td>
                    <td>
                        <!-- Placeholder -->
                    </td>
                    <td>
                        <InformationCircleIcon class="blue-icon" v-tooltip="{ content: 'More testing needed before dual-stack becomes default', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                    <td>
                        <InformationCircleIcon class="blue-icon" v-tooltip="{ content: 'Dual-Stack may already work, but needs more testing', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                    <td>
                        <InformationCircleIcon class="blue-icon" v-tooltip="{ content: 'May switch to dual-stack as the default', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                    <td>
                        <InformationCircleIcon class="blue-icon" v-tooltip="{ content: 'May switch to dual-stack as the default', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                </tr>
            </tbody>
        </table>
    </div>

    <span class="mt-2">The information shown is based on testing. A client may support a feature, but it might not have worked due to network conditions or incorrect configuration.</span>

    <h3 class="text-center my-2">Execution Layer</h3>
    <div class="overflow-x-auto">
        <table class="w-full">
            <thead>
                <tr>
                    <th></th>
                    <th>Nethermind</th>
                    <th>Geth</th>
                    <th>Besu</th>
                    <th>Erigon</th>
                    <th>Reth</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Discv5 Support</td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <InformationCircleIcon class="orange-icon" v-tooltip="{ content: 'Experimental', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                    <td>
                        <InformationCircleIcon class="orange-icon" v-tooltip="{ content: 'Experimental', delay: 0, triggers: ['hover', 'click'] }" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                </tr>
                <tr>
                    <td>Discv5 by Default</td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <CheckCircleIcon class="green-icon" />
                    </td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                    <td>
                        <XCircleIcon class="red-icon" />
                    </td>
                </tr>
            </tbody>
        </table>
    </div>
</template>

<script setup lang="ts">
import { CheckCircleIcon } from '@heroicons/vue/24/outline'
import { InformationCircleIcon } from '@heroicons/vue/24/outline'
import { XCircleIcon } from '@heroicons/vue/24/outline'
</script>

<style scoped>
@reference "@/assets/main.css";

thead>tr>th {
    @apply px-1
}

tbody>tr>td {
    @apply text-center text-nowrap py-0.5
}

td {
    @apply border-t border-zinc-400
}
</style>
