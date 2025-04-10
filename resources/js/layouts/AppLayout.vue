<script setup>
    import SideBar from '@/components/SideBar.vue';
    import TopBar from '@/components/TopBar.vue';
</script>
<template>
    <main class="bg-slate-50">
        <nav class="fixed top-0 left-o right-0 w-full z-30">
            <TopBar />
        </nav>
        <aside class="fixed top-18 left-0 w-70">
            <SideBar />
        </aside>
        <div class="ml-70 pt-18 p-4">
            <slot />
        </div>
    </main>
</template>