<template>
    <div>
        <h2>Article Component</h2>
        <h2 v-bind="$attrs">{{ title }}</h2>
        <h2>Likes - {{ likes }}</h2>
        <h2>Is it Publish ? - {{ isPublished ? 'Yes' : 'No' }}</h2>
    </div>
</template>

<script>
    export default {
        name: 'MeetArticle',
        props: {
            title: {
                type: String,
                required:true,
                default: 'Article default title'
            },
            likes: Number,
            isPublished: Boolean,
           
        },
         inheritAttrs: false,
    }
</script>

<style scoped>

</style>