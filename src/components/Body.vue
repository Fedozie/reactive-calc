<template>
    <div id="container">
        <input type="number" v-model.number="num1">
        <span>+</span>
        <input type="number" v-model.number="num2">
        <span>=</span>
        <span>{{num1 + num2}}</span>
    </div>
</template>

<script>
export default {
    data(){
        return{
            num1: 0,
            num2: 0
        }
    }
}
</script>

<style scoped>
    #container{
        background-color: #42b983;
        height: 300px;
        width: 600px;
        padding-top: 20px;
        margin: 0 auto;
        border-radius: 10px;
    }

    input, span{
        padding: 10px;
        font-size: 30px;
        font-family: 'Work Sans', sans-serif;
    }

    input{
        width: 40px;
        text-align: center;
    }

    span:last-of-type{
        background-color: #9bfcd0;
        width: 60px;
        border-radius: 5px;
    }
</style>