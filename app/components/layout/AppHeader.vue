<script lang="ts" setup>

</script>

<template>
    <header class="app-header">
        <div class="container">
            <div class="logo">
                <h1>Sushi Shop</h1>
            </div>
            <nav class="app-nav nav">
                <ul class="nav_list-link">
                    <li>
                        <NuxtLink to="/">Главная</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="/catalog/menu">Меню</NuxtLink>
                    </li>
                    <li>
                        <NuxtLink to="about">O нас</NuxtLink>
                    </li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<style lang="scss" scoped>
    .logo h1 {
        text-align: center;
        color: lab(84.98% -11.14 83.25);
        font-size: 24px;
        font-weight: 700;
        font-family: Roboto, sans-serif;
    }

    .nav_list-link {
        display: flex;
        align-items: center;
        gap: 20px;
    }
</style>
