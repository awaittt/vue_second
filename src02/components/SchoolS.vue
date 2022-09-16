<template>
    <div class="demo">
        <div>学校名称{{name}}</div>
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
        
    }
  }
  
</script>

<style>
     .demo{
        background-color: pink;
     }
</style>