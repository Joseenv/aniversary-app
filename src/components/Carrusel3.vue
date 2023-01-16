<template>
    <h2>El conejo</h2>
    <div class="carrusel">
        <a href="" class="carrusel__link">
            <img src="@/assets/12.jpeg" alt="" class="img__carrusel">
        </a>
        <a href="" class="carrusel__link">
            <img src="@/assets/10.jpeg" alt="" class="img__carrusel">
        </a>
        <a href="" class="carrusel__link">
            <img src="@/assets/11.jpeg" alt="" class="img__carrusel">
        </a>
        <a href="" class="carrusel__link">
            <img src="@/assets/9.jpeg" alt="" class="img__carrusel">
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