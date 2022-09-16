<template>
  <div class="container">
   <SearchS/>
    <ListS/>
  </div>
</template>

<script>
import SearchS from './components/SearchS'
import ListS from './components/ListS'

export default {
    
    name:'App',
    components:{
    SearchS,
    ListS,
    }
}
</script>

