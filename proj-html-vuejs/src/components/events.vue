<script>
export default {
    name: "events",
    data() {
        return {

        }
    },
}
</script>

<template>
    <div class="container-lg mb-5">
        <div class="row d-flex justify-content-center">
            <div class="col-8 position-relative">
                <div>
                    <img id="video" src="../assets/img/video-bg-3.jpg" alt="">
                </div>
                <div id="event" class="position-absolute px-5 pb-5">
                    <div id="title" class="text-center p-3">Upcoming Events</div>
                    <p class="mt-5">Princeton offers admission information sessions and student-led tours to campus visitors
                    </p>
                    <a>Learn more <small>></small></a>
                    <p class="mt-3">Admission information sessions and student-led tours to campus visitors
                    </p>
                    <a>Learn more <small>></small></a>
                    <div class="text-center mt-5">Event location <small>></small></div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
@use './style/partials/variables.scss' as *;

#video {
    width: 60%;
}

#event {
    width: 60%;
    min-height: 400px;
    background-color: $bgColor1;
    top: 15%;
    left: 40%;
    box-shadow: 0px 21px 50px 8px rgba(0, 0, 0, 0.08);

    #title {
        background-color: $bgColor6;
        color: $textColor1;
        margin: 0 25%;
        font-size: 1.2rem;
    }

    a {
        text-decoration: none;
        color: $textColor11;
        font-weight: bold;
        font-size: 0.8rem;
    }
}
</style>