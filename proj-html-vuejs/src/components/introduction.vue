<script>
export default {
    name: "introduction",
    data() {
        return {

        }
    },
}
</script>

<template>
    <div class="container-fluid">
        <div class="row d-flex justify-content-center" id="presentation">
            <div class="col-6">
                <p>Since 2000, weve been partnering with education leaders to <span>increase equity and
                        achievement</span>
                    for all students.
                </p>
            </div>
        </div>
        <div class="row d-flex justify-content-center">
            <div class="col-8">
                <div class="row text-center">
                    <div class="col-4">
                        <div class="myCard text-center">
                            <img src="../assets/svg/svg-0.svg" alt="">
                            <div class="fw-bold">Online Coaching</div>
                            <p>Loren ipsum is simply dummy text of the print ing and typesetting has been the industrys.</p>

                        </div>
                    </div>
                    <div class="col-4">
                        <div class="myCard text-center">
                            <img src="../assets/svg/svg-1.svg" alt="">
                            <div class="fw-bold">Consultaion</div>
                            <p>Loren ipsum is simply dummy text of the print ing and typesetting has been the industrys.</p>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="myCard text-center">
                            <img src="../assets/svg/svg-2.svg" alt="">
                            <div class="fw-bold">Life Programs</div>
                            <p>Loren ipsum is simply dummy text of the print ing and typesetting has been the industrys.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="row d-flex justify-content-center">
            <div class="col-8">
                <div class="row">
                    <div class="col-4">
                        <div class="d-flex align-items-center ml-1">
                            <div class="fw-bold fs-2 orange mr-1" id="counterStudents">6500</div>
                            <div class="fw-bold fs-2 orange mr-1">+</div>
                            <div class="fw-bold">Students</div>
                        </div>
                    </div>
                    <div class="col-4 numbers">
                        <div class="d-flex align-items-center ml-1">
                            <div class="fw-bold fs-2 red mr-1" id="counterCourses">200</div>
                            <div class="fw-bold fs-2 red mr-1">+</div>
                            <div class="fw-bold">Online Courses</div>
                        </div>
                    </div>
                    <div class="col-4">
                        <div class="d-flex align-items-center ml-1">
                            <div class="fw-bold fs-2 green mr-1" id="counterClients">100</div>
                            <div class="fw-bold fs-2 green mr-1">%</div>
                            <div class="fw-bold">Happy Clients</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
#presentation {
    text-align: center;
    margin-bottom: 4rem;

    p {
        font-size: 26px;
    }
}

.myCard {
    width: 100%;
    padding: 3rem;
    box-shadow: 0px 21px 50px 8px rgba(0, 0, 0, 0.08);
    margin-bottom: 3rem;

    img {
        width: 30%;
        margin-bottom: 1.5rem;
    }

    div {
        margin-bottom: 1.5rem;
    }

    &:hover div {
        color: #D74D52;
    }
}

#counterStudents {
    background-image: url(../assets/img/counter-shape-1-1-1.png);
    background-size: contain;
}

#counterCourses {
    background-image: url(../assets/img/counter-shape-2-1-1.png);
    background-size: contain;
}

#counterClients {
    background-image: url(../assets/img/counter-shape-3-1-1.png);
    background-size: contain;
}

.orange {
    color: #F28202;
}

.red {
    color: #D74D52;
}

.green {
    color: #3ADC79;
}

.mr-1 {
    margin-right: 1rem;
}

.ml-1 {
    margin-left: 1rem;
}

.container-fluid {
    margin-bottom: 4rem;
}
</style>