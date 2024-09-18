<template>
    <div class="flex-1 flex flex-col min-w-80 m-5 max-w-3xl">
        <div class="overflow-x-auto">
            <table>
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
                        <td>Listening IPv6</td>
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
                        <td>Listening Dual-Stack</td>
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
                        <td>Dual-Stack by default</td>
                        <td>
                            <XCircleIcon class="red-icon" />
                        </td>
                        <td>
                            <XCircleIcon class="red-icon" />
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
                            <InformationCircleIcon class="orange-icon" v-tooltip="'The IPv6 address was not automatically detected'" />
                        </td>
                        <td>
                            <InformationCircleIcon class="orange-icon" v-tooltip="'The IPv6 address was not automatically detected'" />
                        </td>
                        <td>
                            <InformationCircleIcon class="orange-icon" v-tooltip="'The IPv6 address was not automatically detected'" />
                        </td>
                        <td>
                            <InformationCircleIcon class="orange-icon" v-tooltip="'The IPv6 address was not automatically detected'" />
                        </td>
                        <td>
                            <InformationCircleIcon class="orange-icon" v-tooltip="'The IPv6 address was not automatically detected'" />
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
                </tbody>
            </table>
        </div>
        <span class="mt-2 text-base">The information shown is based on testing. A client may support a feature, but it might not have worked due to network conditions or incorrect configuration.</span>

        <Config />
    </div>
</template>

<script setup lang="ts">
import { CheckCircleIcon } from '@heroicons/vue/24/outline'
import { InformationCircleIcon } from '@heroicons/vue/24/outline'
import { XCircleIcon } from '@heroicons/vue/24/outline'
import Config from '@/components/Config.vue'
</script>

<style>
thead>tr>th {
    @apply px-1
}

tbody>tr>td {
    @apply text-center text-nowrap
}

td {
    @apply border-t border-zinc-500
}
</style>
