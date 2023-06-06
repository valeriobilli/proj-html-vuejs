<script>

import introduction from './introduction.vue'
import courses from './courses.vue'
import events from './events.vue'
import latestBlog from './latestBlog.vue'

export default {
    name: "PageMain",
    components: {
        introduction,
        courses,
        events,
        latestBlog
    }
}
</script>

<template>
    <introduction></introduction>
    <courses></courses>
    <events></events>
    <latestBlog></latestBlog>
</template>

<style scoped lang="scss"></style>