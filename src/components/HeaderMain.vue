<template>
    <header>
        <img src="@/assets/netflix-logo.svg" alt="">
        <div class="header__wrapper">
            <img src="@/assets/share.svg" alt="">
            <img src="@/assets/profile.jpeg" alt="" class="profile">
        </div>
    </header>
</template>

<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 12px;
        margin-top: 32px;
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
    .profile {
        width: 24px;
        height: 24px;
        object-fit: cover;
    }
</style>