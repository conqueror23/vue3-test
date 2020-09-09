<template>
    <div class="customized-wrapper">

        <div>
            <h1> Section Title here</h1>

            <p> 
            {{real}}
            </p>
        </div>
    </div>
</template>

<script>
    export default{
    name:"customized",
    data() {
        return {
            real:'funny'
        };
    }
    }
</script>

<style scoped>

</style>
