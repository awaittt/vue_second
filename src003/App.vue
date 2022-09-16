<template>
        
        <div>
        
            <SchoolS/>
             <StudentS/>

        </div>

</template>

<script>
import SchoolS from './components/SchoolS.vue'
import StudentS from './components/StudentS.vue'


export default {
    name:'App',
    components:{
        SchoolS,
        StudentS,
    },
    methods:{
     
    }
    
}
</script>

<style>

</style>