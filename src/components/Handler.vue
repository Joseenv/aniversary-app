<template>
   <div class="actions">
    <div class="add">
        <img src="@/assets/add.svg" alt="">
        <span>Mi lista</span>
    </div>
    <div class="play">
        <img src="@/assets/play.svg" alt="">
        <span>Reproducir</span>
    </div>
    <div class="info">
        <img src="@/assets/info.svg" alt="">
        <span>Info</span>
    </div>
   </div>
</template>

<style scoped>
.actions {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1rem;
    top: 0;
    left: 0;
    width: 100%;
    margin-top: 10px;
    font-size: 14px;
}
.add, .info {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 8px;
    width: 10rem;
    flex-direction: column;
}
.play {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 8px;
    width: 10rem;
    background-color: #fff;
    color: #000;
    padding: 8px 16px;
    border-radius: 4px;
}
</style>