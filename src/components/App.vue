<template>
    <div>
        the app
        <MyButton>enter</MyButton>
    </div>
</template>

<script>
    import MyButton from './MyButton.vue'

    export default {
        name: 'App',
        created(){
            console.log('created')
        },
        components: {MyButton}
    }
</script>

<style lang="less">
@bg:#ccc;
body{
    background-color:@bg;
}
</style>