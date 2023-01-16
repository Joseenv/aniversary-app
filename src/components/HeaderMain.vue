<template>
    <header>
        <img src="@/assets/netflix-logo.png" alt="">
        <div class="header__wrapper">
            <img src="@/assets/share.png" alt="">
            <img src="@/assets/profile.png" alt="">
        </div>
    </header>
</template>

<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 12px;
        margin-top: 52px;
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
    }

    .header__wrapper {
        display: flex;
        justify-content: flex-end;
        align-items: center;
        gap: 1rem;
        width: 10rem;
    }
</style>