<template>
    <h1>{{dados}}</h1>
</template>

<script>
export default {
    name: 'Texts',
    props: {
        dados: {
            type: String,
            required: true
        }
    },
     
}
</script>
