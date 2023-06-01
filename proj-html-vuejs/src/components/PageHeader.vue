<script>
export default {
    name: "PageHeader",
    props: {
        navLinks: Array,
    },
    data() {
        return {

        }
    },
}
</script>

<template>
    <header>
        <div class="container-fluid">
            <div class="row d-flex justify-content-center align-items-center position-relative" id="navbar">
                <div class="col-8 d-flex justify-content-between align-items-center">
                    <img src="../assets/img/Logo.jpg" alt="Logo" id="logoHeader">
                    <div class="links">
                        <a v-for="link in navLinks">{{ link }}</a>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="col-12" id="jumbo">
                    <h1 class="text-center">Professional Development For Coaches And Leaders</h1>
                    <div class="d-flex justify-content-center align-items-center">
                        <button type="button" class="btn btn-outline-dark" id="learnMoreBtn">Learn More</button>
                    </div>
                </div>
            </div>
        </div>
    </header>
</template>

<style scoped lang="scss">
#navbar {
    height: 75px;
    z-index: 1;
}

#logoHeader {
    width: 145px;
    height: 110px;
    z-index: 2;
}

a {
    margin-right: 1rem;
}

#jumbo {
    height: 90vh;
    background-image: url(../assets/img/jumbotron_1.PNG);
    background-size: cover;
    background-position: center;
    margin-bottom: 2rem;

    h1 {
        width: 750px;
        font-size: 45px;
        margin: 10% auto 3rem;
    }
}
</style>