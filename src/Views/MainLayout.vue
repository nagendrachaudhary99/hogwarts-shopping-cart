<template>
    <div class="main-layout">
        <Navigation></Navigation>
        <router-view v-slot="{ Component, route }">
            <transition :enter-active-class="route.meta.enterAnimation || 'animate__animated animated__fadeIn'" :leave-active-class="route.meta.leaveAnimation || 'animate__animated animate__fadeOut'"
                mode="out-in">
                <component :is="Component"></component>
            </transition>
        </router-view>
    </div>
</template>

<script setup>
import Navigation from '@/components/Navigation.vue';
</script>

<style lang="scss" scoped>
.main-layout {
    display: flex;
    flex-direction: column;
    gap: 1rem;
}
</style>