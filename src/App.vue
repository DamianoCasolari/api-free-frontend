<script>
import appHeader from './components/appHeader.vue'

export default {
    components: {
        appHeader
        }
}
</script>

<template>
    <div class="Web_page">
        <appHeader />
        <main>
            <router-view></router-view>
        </main>
    </div>
</template>

<style lang="scss"></style>
