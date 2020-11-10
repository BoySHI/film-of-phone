<template>
    <div class="main">
        <Header></Header>
        <div class="content">
            <div class="movie_menu">
                <router-link to="/movie/City" class="city_name" tag="div">
                    <span>北京</span>
                </router-link>
                <div class="hot_switch">
                    <router-link to="/movie/NowPlaying" class="hot_item" tag="div">正在热映</router-link>
                    <router-link to="/movie/ComingSoon" class="hot_item" tag="div">即将上映</router-link>
                </div>
                <router-link to="/movie/Search" class="search_entry" tag="div">
                    <i class="fa fa-search" aria-hidden="true"></i>
                </router-link>
            </div>
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
export default {
    components:{
        Header,
        TabBar
    }
}
</script>

<style scoped>
    .content .movie_menu{
        width: 100%;
        height: 45px;
        border-bottom:1px solid #e6e6e6;
        display: flex;
        justify-content: space-between;
    }
    .movie_menu .city_name{
       margin-left: 20px;
       height: 100%;
       line-height: 45px; 
       cursor: pointer;
    }
    .movie_menu .city_name.router-link-active{
        color: #ef4238;
        border-bottom: 2px solid #ef4238;
        box-sizing:border-box
    }
    .movie_menu .hot_switch{
        display: flex;
        height: 100%;
        line-height: 45px; 
    }
    .movie_menu .hot_item{
        font-size: 15px;
        color: #666;
        width: 80px;
        text-align: center;
        margin: 0 12px;
        font-weight: 700;
        cursor: pointer;
    }
    .movie_menu .search_entry{
        line-height: 45px;
        font-size: 16px;
        cursor: pointer;
        margin: 0 15px;
    }
    .movie_menu .hot_item.router-link-active{
        color: #ef4238;
        border-bottom: 2px solid #ef4238;
        box-sizing:border-box
    }
</style>