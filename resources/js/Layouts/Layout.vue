<script setup>

import {switchTheme} from "../theme.js";
</script>

<template>
    <div class="min-h-screen">

        <header>
            <!-- NAVBAR -->
            <nav class="bg-white dark:bg-slate-800 border-b border-gray-200 dark:border-slate-700">
                <div class="max-w-7xl mx-auto px-6">
                    <div class="flex justify-between h-16 items-center">

                        <!-- LOGO -->
                        <div class="flex items-center space-x-2">
                            <Link :href="route('home')" class="text-xl font-bold text-indigo-600">
                              SmartWallet
                            </Link>
                        </div>

                        <!-- MENU -->
                        <div class="hidden md:flex items-center space-x-6">

                            <Link href="#" class="hover:text-indigo-600">
                                Dashboard
                            </Link>

                            <Link href="#" class="hover:text-indigo-600">
                                Transactions
                            </Link>

                            <Link href="#" class="hover:text-indigo-600">
                                Reports
                            </Link>

                        </div>

                        <!-- USER -->
                        <div class="flex items-center space-x-4">

                            <!-- Theme toggle -->
                            <button
                                class="p-2 rounded-lg hover:bg-gray-100 dark:hover:bg-slate-700 transition cursor-pointer"
                                @click="switchTheme()"
                            >
                                <i class="fa-solid fa-circle-half-stroke"></i>
                            </button>

                            <!-- User avatar -->
                            <div
                                class="w-8 h-8 flex items-center"
                            >
                                Hello, <b>USER</b>
                                <img src="/public/images/default/default.jpg" class="rounded-full ml-2" alt="profile">
                            </div>
                        </div>

                    </div>
                </div>
            </nav>
        </header>

        <!-- PAGE CONTENT -->
        <main class="max-w-7xl mx-auto px-6 py-8">
            <slot />
        </main>
    </div>
</template>

<style scoped>

</style>
