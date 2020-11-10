<template>
    <header id="header">
        <h1>{{title}}</h1>
    </header>
</template>

<script>
export default {
    name:'Header',
    props:{
        title:{
            type:String,
            default:'掌上电影'
        }
    }
}
</script>

<style scoped>
    #header{
        width: 100%;
        height: 50px;
        color: #fff;
        background:#e54847;
        border: 1px solid #e54847;
    }
     #header h1{
        text-align: center;
        font-size: 18px;
        line-height: 50px;
        font-weight: 400;
    }
</style>