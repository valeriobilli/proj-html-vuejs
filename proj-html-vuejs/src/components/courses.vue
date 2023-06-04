<script>
export default {
    name: "courses",
    data() {
        return {

        }
    },
}
</script>

<template>
    <div class="container-fluid">
        <!-- recent courses -->
        <div class="row d-flex justify-content-center">
            <div class="col-5">
                <div class="row text-center">
                    <h3>Recent courses</h3>
                    <div>Whether you're considering a foundation course or an undergraduate degree master's or a PhD,
                        Academics is a place where students thrive.</div>
                </div>
            </div>
        </div>
        <!-- cards -->
        <div class="row d-flex justify-content-center">
            <div class="col-8">
                <div class="row">
                    <div class="col-4">
                        <div class="imageCard">
                            <img src="../assets/img/bruce-mars-FWVMhUa_wbY-unsplash.jpg" alt="">
                            <div class="cardText">
                                <div class="free mb-1">Free</div>
                                <div class="fw-bold mb-1">UI Animation using Sketch 3, Principle App, and Flinto</div>
                                <div>This online Photography course will teach you how to take amazing images and even
                                    sell...</div>
                                <div>Course by: University</div>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="imageCard">
                            <img src="../assets/img/course-1-2.jpg" alt="">
                            <div class="cardText">
                                <div class="free">Free</div>
                                <div class="fw-bold">The Ultimate Drawing Course <br />
                                    -Beginner to Advanced</div>
                                <div>This online Photography course will teach you how to take amazing images and even
                                    sell...</div>
                                <div>Course by: University</div>
                            </div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="imageCard">
                            <img src="../assets/img/william-thomas-ny6tO4ItOEY-unsplash.jpg" alt="">
                            <div class="cardText">
                                <div class="free">Free</div>
                                <div class="fw-bold">Your Complete Guide to Photography</div>
                                <div>This online Photography course will teach you how to take amazing images and even
                                    sell...</div>
                                <div>Course by: University</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
.imageCard {
    box-shadow: 0px 21px 50px 8px rgba(0, 0, 0, 0.08);

    img {
        width: 100%;
        height: 195px;
    }

    .cardText {
        padding: 2rem 1rem;
    }
}

.mb-1 {
    margin-bottom: 1rem;
}
</style>