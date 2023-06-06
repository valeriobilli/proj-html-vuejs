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
    <div class="container-lg mb-5">
        <!-- recent courses -->
        <div class="row d-flex justify-content-center">
            <div class="col-5">
                <div class="row text-center mb-4">
                    <h3 class="mb-3">Recent Courses</h3>
                    <div>Whether you're considering a foundation course or an undergraduate degree master's or
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
                            <img src="../assets/img/bruce-mars-FWVMhUa_wbY-unsplash.jpg" alt="">
                            <div class="cardText">
                                <div class="free mb-1">Free</div>
                                <div class="fw-bold mb-1">UI Animation using Sketch 3, Principle App, and Flinto</div>
                                <div>This online Photography course will teach you how to take amazing images and even
                                    sell...</div>
                                <div class="university">Course by: University</div>
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
                                <div class="university">Course by: University</div>
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
                                <div class="university">Course by: University</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- quote -->
        <div class="row d-flex justify-content-center">
            <div class="col-8">
                <p id="quote" class="mt-2">"Academics was committed to my success from the moment I attend an Open House.
                    With the
                    support of caring
                    <span class="fw-bold red">advisors, professors, and staff</span> I was able to thrive in courses, gain
                    recognition trough
                    scholarhip, and finish <span class="fw-bold">with confidence in my <span
                            class="fw-bold red">@academics</span> abilities.</span>"
                </p>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use './style/partials/variables.scss' as *;

.imageCard {
    height: 450px;
    box-shadow: 0px 21px 50px 8px rgba(0, 0, 0, 0.08);
    position: relative;

    img {
        width: 100%;
        height: 180px;
    }

    .cardText {
        padding: 2rem 1rem;

        .university {
            color: $textColor6;
            font-size: 0.8rem;
            position: absolute;
            bottom: 1.5rem,
        }
    }
}

#quote {
    font-size: 1.5rem;
    text-align: center;
    background-image: url("../assets/img/quote.png");
    background-repeat: no-repeat;
    background-position: center;

    .red {
        color: $textColor6;
        text-decoration: underline;
    }
}
</style>