<template>
    <div class="demo">
        <div @click="showName">学生姓名{{name}}</div>
        <div>学生年龄{{age}}</div>
    </div>

</template>

<script>
  export default {
    name:'StudentS',
    data(){
        return{
        name:'孙一达',
        age:18,
        }
        
    },
     methods:{
      showName(){
        alert(this.name)
      }
    }
  }
</script>

<style>
     .demo{
        background-color: #bfa;
     }
</style>