<template>
    <div class="demo">
        <div @click="showName">学校名称{{name}}</div>
        <div>学生地址{{adress}}</div>
    </div>

</template>

<script>
  export default {
    name:'SchoolS',
    data(){
        return{
        name:'巍山中学',
        adress:'惠安县',
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
        background-color: pink;
     }
</style>