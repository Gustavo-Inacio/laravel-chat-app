<script setup>
import AppLayout from '@/Layouts/AppLayout.vue';
import Welcome from '@/Components/Welcome.vue';
</script>

<template>
    <AppLayout title="Dashboard">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Chat
            </h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg flex" style="height: 80vh">
<!--                    List Users-->
                    <div class="w-3/12 bg-gray-200 bg-opacity-25 border-r border-gray-200 overflow-y-auto">
                        <ul>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-opacity-50 hover:cursor-pointer hover:bg-gray-200">
                                <p class="flex items-center">
                                    Teste do GUGAA
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                        </ul>
                    </div>

                    <div class="w-9/12 flex-col flex justify-between">

<!--                        message-->
                        <div class="w-full p-6 flex flex-col overflow-y-auto">
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageFromMe" style="max-width: 75%">
                                    Olá!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageToMe" style="max-width: 75%">
                                    Oi!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageFromMe" style="max-width: 75%">
                                    Olá!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageToMe" style="max-width: 75%">
                                    Oi!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>

                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageFromMe" style="max-width: 75%">
                                    Olá!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageToMe" style="max-width: 75%">
                                    Oi!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageFromMe" style="max-width: 75%">
                                    Olá!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageToMe" style="max-width: 75%">
                                    Oi!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>

                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageFromMe" style="max-width: 75%">
                                    Olá!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageToMe" style="max-width: 75%">
                                    Oi!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageFromMe" style="max-width: 75%">
                                    Olá!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageToMe" style="max-width: 75%">
                                    Oi!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>

                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageFromMe" style="max-width: 75%">
                                    Olá!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageToMe" style="max-width: 75%">
                                    Oi!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageFromMe" style="max-width: 75%">
                                    Olá!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageToMe" style="max-width: 75%">
                                    Oi!
                                </p>
                                <span class="block md-1 text-xs text-gray-500">
                                    29/09/2024 17:12
                                </span>
                            </div>
                        </div>

                        <form class="w-full bg-gray-200 bg-opacity-25 p-6 border-t border-gray-600 flex">
                            <input type="text" class="flex-1 px-4 py-2 text-sm focus:outline-none border-gray-300 border-r-2">
                            <button type="submit" class="bg-indigo-500 hover:bg-indigo-600 text-white px-4 py-2">Enviar</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </AppLayout>
</template>

<style>
.messageFromMe {
    @apply bg-indigo-300 bg-opacity-25
}

.messageToMe {
    @apply bg-gray-200 bg-opacity-25
}

</style>
