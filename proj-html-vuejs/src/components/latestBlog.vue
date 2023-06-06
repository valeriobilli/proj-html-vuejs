<script>
export default {
    name: "latestBlog",
    data() {
        return {

        }
    },
}
</script>

<template>
    <div class="container-lg mb-5">
        <!-- recent courses -->
        <div class="row d-flex justify-content-center">
            <div class="col-5">
                <div class="row text-center mb-4">
                    <h3 class="mb-3">Latest From Our Blogs</h3>
                    <div class="mb-4">Whether you're considering a foundation course or an undergraduate degree master's or
                        a PhD,
                        Academics is a place where students thrive.</div>
                </div>
            </div>
        </div>
        <!-- cards -->
        <div class="row d-flex justify-content-center mb-5">
            <div class="col-8">
                <div class="row">
                    <div class="col-4">
                        <div class="imageCard">
                            <img src="../assets/img/news-3-2.jpg" alt="">
                            <div class="cardText">
                                <span class="me-5">Admin</span>
                                <span>University</span>
                                <div class="fw-bold mt-3 mb-1">Peer pressure changes how teens tackle inequality</div>
                                <div class="redLine"></div>
                                <span class="mt-5">Read More <small>></small></span>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="imageCard">
                            <img src="../assets/img/news-2-2.jpg" alt="">
                            <div class="cardText">
                                <span class="me-5">Admin</span>
                                <span>Education</span>
                                <div class="fw-bold mt-3">Lewisham Live Mixtape celebrates brough's</div>
                                <div class="redLine"></div>
                                <span class="mt-5">Read More <small>></small></span>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="imageCard">
                            <img src="../assets/img/news-1-2.jpg" alt="">
                            <div class="cardText">
                                <span class="me-5">Admin</span>
                                <span>Education</span>
                                <div class="fw-bold mt-3">Turner Prize winner's work to open Gold on Film festival</div>
                                <div class="redLine"></div>
                                <span class="mt-5">Read More <small>></small></span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- quote -->
    </div>
</template>

<style scoped lang="scss">
h3 {
    margin-top: 5rem;
}

.imageCard {
    box-shadow: 0px 21px 50px 8px rgba(0, 0, 0, 0.08);

    img {
        width: 100%;
        height: 160px;
    }

    .cardText {
        padding: 2rem 1.5rem;

        span {
            font-size: 0.8rem;
            margin-top: 5rem;
        }

        .redLine {
            width: 50px;
            height: 2px;
            background-color: red;
            margin-top: 1rem;
            margin-bottom: 3rem;
        }
    }
}
</style>