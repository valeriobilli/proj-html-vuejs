<script>

import introduction from './introduction.vue'
import courses from './courses.vue'

export default {
    name: "PageMain",
    components: {
        introduction,
        courses
    }
}
</script>

<template>
    <introduction></introduction>
    <courses></courses>
</template>

<style scoped lang="scss"></style>