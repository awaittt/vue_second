<template>
  <div>
    <img src="./assets/logo.png" alt="logo" >
    <SchoolS></SchoolS>
    <StudentS></StudentS>
  </div>
</template>

<script>
import SchoolS from './components/SchoolS'
import StudentS from './components/StudentS'

export default {
    
    name:'App',
    components:{
        SchoolS,
        StudentS,
    }
}
</script>

