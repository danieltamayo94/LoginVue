<template>
    <button>{{ msgButton }}</button>
</template>

<script>
export default {
    name: 'ButtonInput',
    props: {
        msgButton: String
    },
}
</script>