<template>
    <h2>
        Hello {{name}} a.k.a {{ heroName }}
    </h2>
</template>

<script>
    export default {
        name: "MeetGreet",
        props: ['name','heroName']
    };
</script>

<style scoped>

</style>