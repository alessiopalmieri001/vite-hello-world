<script >
    
    export default {
        data() {
            return { 
                title: 'La mia prima app con Vite!'
            };
        },
        
        
    };
</script>


<template>
    
        <h1>
            {{ title }}
        </h1>
    
</template>

<style scoped>
    h1{
    text-align: center;
    font-weight: bold;
    background-color: blue;
    padding: 20px;
}
</style>