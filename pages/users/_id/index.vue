<template>
    <h1>A single users, with ID: {{ $route.params.id }}</h1>
</template>


<script>

    export default {
        validate (data) {
            return /^\d+$/.test(data.params.id)
        },
        
        layout: 'users',
    }

</script>