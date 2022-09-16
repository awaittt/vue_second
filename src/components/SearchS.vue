<template>
   <section class="jumbotron">
      <h3 class="jumbotron-heading">Search Github Users</h3>
      <div>
        <input type="text" placeholder="enter the name you search" v-model="keyword" />&nbsp;
        <button @click="getUser">Search</button>
      </div>
    </section>
</template>

<script>
import axios from 'axios'
export default {
    name:'SearchS',
    data(){
      return {
        keyword:'',

      }
    },
    methods:{
      getUser(){
        axios.get(`https://api.github.com/search/users?q=${this.keyword}`).then((ret)=>{
                if(ret){
                  console.log('我成功了')
                }else{
                  console.log('我失败了')
                }
        })
      }
    }
}
</script>

<style>

</style>