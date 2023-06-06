<script>

import introduction from './introduction.vue'
import courses from './courses.vue'
import events from './events.vue'

export default {
    name: "PageMain",
    components: {
        introduction,
        courses,
        events
    }
}
</script>

<template>
    <introduction></introduction>
    <courses></courses>
    <events></events>
</template>

<style scoped lang="scss"></style>