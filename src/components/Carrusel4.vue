<template>
    <h2>Convivencia</h2>
    <div class="carrusel">
        <a href="" class="carrusel__link">
            <img src="@/assets/13.jpeg" alt="" class="img__carrusel">
        </a>
        <a href="" class="carrusel__link">
            <img src="@/assets/14.jpeg" alt="" class="img__carrusel">
        </a>
        <a href="" class="carrusel__link">
            <img src="@/assets/15.jpeg" alt="" class="img__carrusel">
        </a>
        <a href="" class="carrusel__link">
            <video src="@/assets/16.mp4" alt="" class="img__carrusel" preload="auto" autoplay loop></video>
        </a>
    </div>
</template>

<style scoped>
h2 {
    font-size: 16px;
    padding: 0 12px;
    margin-top: 24px;
    color: #fff;
    font-weight: 700;
    margin-bottom: 16px;
}
.carrusel {
    display: flex;
    overflow-x: scroll;
    align-items: center;
    padding: 0 12px;
    gap: 8px;
    margin-bottom: 24px;
}
.carrusel__link {
    width: 100px;
    height: 141px;
    overflow-x: scroll;
}
.img__carrusel {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 8px;
}
</style>