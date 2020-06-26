<template>
 <div>
   home
   <Nav-header></Nav-header>
   <route-view></route-view>
   <Nav-footer></Nav-footer>
 </div>
</template>
<script>
import NavHeader from '../components/NavHeader'
import NavFooter from '../components/NavFooter'
  export default{
    name:'nav-home',
    components:{
      NavFooter,
      NavHeader
    }
  }
</script>