<script>
export default {
    name: "PageFooter"
}
</script>

<template>
    <div class="d-flex">
        <div class="col">
            <img src="../assets/img/gallery-3-3.jpg" alt="">
        </div>
        <div class="col">
            <img src="../assets/img/news-3-2.jpg" alt="">
        </div>
        <div class="col">
            <img src="../assets/img/gallery-2-3.jpg" alt="">
        </div>
        <div class="col">
            <img src="../assets/img/gallery-1-3.jpg" alt="">
        </div>
    </div>

    <footer>
        <div class="container-lg">
            <div class="row d-flex justify-content-center">
                <div class="col-8 d-flex">
                    <div>ciao</div>
                    <div>ciao</div>
                </div>
            </div>
        </div>
    </footer>
</template>



<style scoped lang="scss">
@use './style/partials/variables.scss' as *;

.col {
    width: calc(100vh / 4);
    height: 300px;

    img {
        width: 100%;
        height: 300px;
    }
}

footer {
    height: 650px;
    background-color: $bgColor9;
    border-top: 1px solid $borderColor1;
}
</style>