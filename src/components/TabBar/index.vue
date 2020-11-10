<template>
    <footer id="footer">
        <ul>
            <router-link tag="li" to="/movie">
            <i class="fa fa-film" aria-hidden="true"></i>
                <p>电影</p>
            </router-link>
            <router-link tag="li" to="/cinema">
            <i class="fa fa-youtube-square" aria-hidden="true"></i>
                <p>影院</p>
            </router-link>
            <router-link tag="li" to="/mine">
                <i class="fa fa-user-circle" aria-hidden="true"></i>
                <p>我的</p>
            </router-link>
        </ul>
    </footer>
</template>

<script>
export default {
    name:'TabBar'
}
</script>

<style  scoped>
#footer{
    width: 100%;
    height: 50px;
    background: #fff;
    border: 1px solid #ebe8e3;
    position: fixed;
    bottom: 0;
    left: 0;
}
#footer ul{
    display: flex;
    text-align: center;
    height: 50px;
    align-items: center;
}
#footer ul li{
    flex:1;
    height: 40px;
}
#footer ul p{
    font-size: 12px;
    line-height: 18px;
}
#footer ul i{
    font-size: 20px;
}
</style>