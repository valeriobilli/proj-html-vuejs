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
    <div class="container-fluid">
        <div class="row d-flex justify-content-center align-items-center" id="navbar">
            <div class="col-8">
                <div class="d-flex justify-content-between align-items-center">
                    <img src="../assets/img/Logo.jpg" alt="Logo" id="logoHeader">
                    <div>
                        <a v-for="link in navLinks">{{ link }}</a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped lang="scss">
#navbar {
    height: 75px;
    border-bottom: 1px solid black;
}

#logoHeader {
    width: 145px;
    height: 110px;
}

a {
    margin-right: 1rem;
}
</style>