<template>
    <div class="full">
        <div @click="toggleMenu" class="screen"></div>

        <header class="main-header">
            <div class=" flex justify-between items-center">
                <div class="logo header-logo">
                    <img class="web-icon" src="../images/logo.svg" alt="">
                </div>
                <ul class="main-nav clean-list flex">
                    <li><a href="#">Features</a></li>
                    <li><a href="#">Team</a></li>
                    <li><a href="#">Sign In</a></li>
                </ul>
                <button @click="toggleMenu" class="btn menu-toggle-btn">☰</button>
            </div>
        </header>
    </div>
</template>

<script>
export default {
    methods: {
        toggleMenu() {
            document.body.classList.toggle('menu-open')
        },
    }
}
</script>

<style lang="scss" scoped>
</style>