<template>
    <div>
        {{ greet }}
    </div>
</template>

<script>
export default {
    data:()=>({
        greet:'hello'
    }),
    created(){
        console.log(this.greet)
    }
}
</script>

<style>
body{
    background-color:#eee;
}
</style>