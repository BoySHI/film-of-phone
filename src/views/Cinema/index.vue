<template>
    <div class="main">
        <Header></Header>
        <div class="content">
            <Address></Address>
        <keep-alive>
            <router-view></router-view>
        </keep-alive>
        </div>
         <TabBar></TabBar>
    </div>
     
</template>

<script>
import Header from '../../components/Header'
import Address from '../../components/Address'
import TabBar from '../../components/TabBar'
export default {
   components:{
        Header,
        Address,
        TabBar
       
   }
}
</script>