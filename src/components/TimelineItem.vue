<script setup lang="ts">

defineProps<{
post: TimelinePost
}>()

import { type TimelinePost } from '../posts'


</script>
<template>

<li>
    <span>{{ post.title }}</span>&nbsp;|&nbsp;
    <span>{{ post.created.toFormat("d MMM") }}</span>
</li>   

</template>
<style></style>