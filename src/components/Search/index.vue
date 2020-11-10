<template>
    <div class="search_body">
        <div class="search_input">
            <div class="search_input_wrapper">
            <i class="fa fa-search" aria-hidden="true"></i>
            <input type="text">
            </div>         
        </div>
        <div class="search_result">
            <h3>电影/电视剧/综艺/游戏</h3>
            <ul>
                <li>
                <div class="pic_show">
                    <img src="../../../public/Imgs/005.png" alt="">
                </div>
                <div class="info_list">
                    <p class="one">人鱼缚</p>
                    <p>豆瓣评分：<span class="grade">8.0</span></p>
                    <p>主演：杨敏 井柏然</p>
                    <p>今日50家影院播放500场</p>
                </div>
            </li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name:'Search'
}
</script>


<style  scoped>
.search_body{
    display: flex;
    overflow: auto;
    flex-direction: column;
}
.search_body .search_input{
    padding: 8px 10px;
    background: #f5f5f5;
    border-bottom: 1px solid #e5e5e5;
}
.search_body .search_input_wrapper{
    padding: 0 10px;
    display: flex;
    background: white;
    border: 1px solid #e6e6e6;
}
.search_body .search_input_wrapper i{
    padding:4px 0;
    font-size:16px;
}
.search_body .search_input_wrapper input{
    border: none;
    outline: none;
    padding: 0;
    flex: 1;
}
.search_body .search_result ul li{
    padding: 10px 15px;
    display: flex;
    box-sizing: border-box;
    border-bottom:1px dashed #c9c9c9;
}
.search_body .search_result h3{
    font-size: 15px;
    border-bottom: 1px solid #e6e6e6;
    color: #999;
    padding: 9px 15px;
}
.search_body .search_result .pic_show{
  width: 60px;
}
.search_body .search_result .pic_show img{
    width: 100%;
}
.search_body .search_result .info_list{
    margin-left: 20px;
    flex:1;
    font-size: 12px;
}
.search_body .search_result .info_list p{
    height: 22px;
}
.search_body .search_result .info_list .one{
   font-size: 15px; 
   font-weight: 700;
}
</style>