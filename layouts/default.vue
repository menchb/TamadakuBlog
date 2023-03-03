<template>
    <div class="">
        <header class="float-left ">
            <div class="border-dotted b-2 m-0 h-screen">
                <div class="list-none gap-4 p-4">
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/">Home</NuxtLink>
                    </li>
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/about">About</NuxtLink>
                    </li>
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/people">People</NuxtLink>
                    </li>
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/articles">Articles</NuxtLink>
                    </li>
                </div>
            </div>
            <!-- <div class="border-dotted b-2">
                <div class="flex justify-center gap-4 p-4">
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/">Home</NuxtLink>
                    </li>
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/about">About</NuxtLink>
                    </li>
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/people">People</NuxtLink>
                    </li>
                    <li class="font-bold text-slate-700 hover-outline-groove animate-all 250ms ease-in">
                        <NuxtLink to="/articles">Articles</NuxtLink>
                    </li>
                </div>
            </div> -->
        </header>
        <div class="p-4 mx-auto flex">
            <article class="">
                <h2>Barcelona, City of Love</h2>
                <div class="">
                    <img src="./barcelona.jpg.crdownload">
                    <div class="inline-block align v-top">
                        <span class="block">01</span>
                        <span class="block">3/01/23</span>
                    </div>
                </div>
                <slot />
            </article>
            <article class="w-sm">
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            </article>
        </div>
        <footer class="bg-coolgray overflow-hidden">
            <div>
            <!-- <div class="justify-center align-items gap-2 mx-auto"> -->
                <marquee class="" behavior="string" direction="left">
                    <span>Testing lang po</span>
                    <span>Testing uli HUHUHU</span>
                    <span>Testing uli HUHUHU</span>
                </marquee>
            </div>
        </footer>
    </div>
</template>

<script setup>

</script>

<style scoped>

</style>