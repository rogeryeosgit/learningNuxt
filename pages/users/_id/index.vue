<template>
    <h1>Single User ID: {{ $route.params.id }}</h1>
</template>

<script>
export default {
    validate(data) {
        console.log(data);
        return true;
    }
}
</script>