<script setup>
    import { ref } from 'vue'
</script>
<template>
    <header class="sticky top-0 bg-background/65 backdrop-blur border-b border-border flex z-50">
        <nav class="w-full">
            <div class="flex space-x-4 items-center justify-between mx-6">
                <a href="/" class="mr-6"><div class="flex flex-row items-center"><img width="160px" src="../assets/logo.png" alt="42 Angoulême"></div></a>
                <div class="justify-center items-center">
                    <ul class="text-sm flex space-x-2 select-none h-14">
                        <li class="relative h-full flex flex-col justify-center">PEDAGO</li>
                        <li class="relative h-full flex flex-col justify-center">ISSUES</li>
                        <li class="relative h-full flex flex-col justify-center">VOX</li>
                    </ul>
                </div>
                <div class="flex flex-row space-x-4 items-center">
                    <div class=""></div>
                    <button class="text-center rounded-global-radius h-9 px-4 py-2 text-sm font-bold">Logout</button>
                </div>
            </div>
        </nav>
    </header>
</template>