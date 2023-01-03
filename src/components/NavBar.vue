<template>
    <nav class="w-full pt-4">
        <div class="container mx-auto px-4 w-11/12 relative sm:w-9/12 md:w-7/12">
            <div class="flex items-center justify-between">
                <RouterLink to="/"
                    class="flex-shrink-0 h-10 w-10" aria-current="page">
                    <img src="../assets/cd/wollogovec.png" draggable="false" class="animate-spin-slow rounded-md ring-black transition-transform ring-2 ring-opacity-5 sm:transform hover:rotate-12" alt="icon">
                </RouterLink>
                <!-- <div class="flex space-x-2 items-center"><a target="" rel="noreferrer noopener"
                        class="cursor-pointer flex space-x-2 transition-colors btn items-center justify-center focus:outline-none text-gray-700 dark:text-neutral-400 rounded-full p-2 sm:w-max bg-gray-200 hover:bg-gray-200/40 dark:bg-neutral-800 dark:hover:bg-neutral-800/40"
                        data-tippy-directive="" tabindex="0"><svg xmlns="http://www.w3.org/2000/svg" fill="none"
                            viewBox="0 0 24 24" stroke="currentColor" class="h-5 w-5">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg> 
                    </a> <a target="" rel="noreferrer noopener"
                        class="cursor-pointer flex space-x-2 transition-colors btn items-center justify-center text-gray-700 dark:text-neutral-400 rounded-full p-2 sm:w-max bg-gray-200 hover:bg-gray-200/40 dark:bg-neutral-800 dark:hover:bg-neutral-800/40"><svg
                            xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor"
                            class="h-5 w-5">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M20.354 15.354A9 9 0 018.646 3.646 9.003 9.003 0 0012 21a9.003 9.003 0 008.354-5.646z">
                            </path>
                        </svg> 
                    </a></div> -->
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'NavBar'
}
</script>

<style lang="scss" scoped>

</style>