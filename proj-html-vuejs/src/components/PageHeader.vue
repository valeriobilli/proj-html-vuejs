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
        <div class="row">
            <div class="col-8">
                <div class="">
                    <a v-for="link in navLinks">{{ link }}</a>
                </div>
            </div>
        </div>
    </div>
</template>

<style></style>