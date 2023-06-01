<script>
export default {
    name: "PageMain"
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
                <!-- cards -->
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
}
</style>