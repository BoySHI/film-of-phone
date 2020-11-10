<template>
    <div class="main">
        <Header></Header>
        <div class="content">
           <Login></Login>
            <keep-alive>
                <router-view></router-view>
            </keep-alive>
        </div>
        <TabBar></TabBar>
    </div>
</template>

<script>
import Header from '../../components/Header'
import TabBar from '../../components/TabBar'
import Login from '../../components/Login'
export default {
    components:{
        Header,
        TabBar,
        Login
    }
}
</script>

<style scoped>
    
</style>