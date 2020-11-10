<template>
    <div class="movie_body">
        <ul>
            <li>
                <div class="pic_show">
                    <img src="../../../public/Imgs/001.png" alt="">
                </div>
                <div class="info_list">
                    <h2>山海巨兽</h2>
                    <p>豆瓣评分：<span class="grade">9.0</span></p>
                    <p>主演：李易峰</p>
                    <p>今日50家影院播放500场</p>
                </div>
                <div class="btn_mail">
                    购买
                </div>
            </li>
            <li>
                <div class="pic_show">
                    <img src="../../../public/Imgs/002.png" alt="">
                </div>
                <div class="info_list">
                    <h2>小小鸟</h2>
                    <p>豆瓣评分：<span class="grade">9.0</span></p>
                    <p>主演：特狼皮</p>
                    <p>今日50家影院播放500场</p>
                </div>
                <div class="btn_mail">
                    购买
                </div>
            </li>
            <li>
                <div class="pic_show">
                    <img src="../../../public/Imgs/003.png" alt="">
                </div>
                <div class="info_list">
                    <h2>1917I</h2>
                    <p>豆瓣评分：<span class="grade">9.0</span></p>
                    <p>主演：吴京</p>
                    <p>今日50家影院播放500场</p>
                </div>
                <div class="btn_mail">
                    购买
                </div>
            </li>
            <li>
                <div class="pic_show">
                    <img src="../../../public/Imgs/004.png" alt="">
                </div>
                <div class="info_list">
                    <h2>1917II</h2>
                    <p>豆瓣评分：<span class="grade">9.0</span></p>
                    <p>主演：张毅</p>
                    <p>今日50家影院播放500场</p>
                </div>
                <div class="btn_mail">
                    购买
                </div>
            </li>
            <li>
                <div class="pic_show">
                    <img src="../../../public/Imgs/005.png" alt="">
                </div>
                <div class="info_list">
                    <h2>人鱼缚</h2>
                    <p>豆瓣评分：<span class="grade">8.0</span></p>
                    <p>主演：杨敏</p>
                    <p>今日50家影院播放500场</p>
                </div>
                <div class="btn_mail">
                    购买
                </div>
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    name:'NowPlaying'
}
</script>


<style  scoped>
    .movie_body{
        display: flex;
        overflow: auto;
    }
    .movie_body ul{
        margin: 0 12px;
        overflow: hidden;
     }
    .movie_body ul li{
        display: flex;
        margin-top: 12px;
        margin-left: 30px;
        align-items: center;
        border: 1px solid #e6e6e6;
        padding-bottom: 10px;
    }
    .movie_body .pic_show{
        width: 64px;
        height: 90px;
    }
    .movie_body .pic_show img{
        width: 100%;
    }
    .movie_body .info_list{
        margin-left: 10px;
        flex: 1;
        position: relative;
    }
    .movie_body .info_list h2{
        font-size: 18px;
        line-height: 24px;
        width: 150px;
        overflow: hidden;
        white-space: nowrap;
        text-overflow: ellipsis;       
    }
    .movie_body .info_list p{
         font-size: 13px;
         color: #666;
         line-height: 22px;
         width: 200px;
         overflow: hidden;
        white-space: nowrap;
        text-overflow: ellipsis; 
    }
    .movie_body .info_list .grade{
        font-weight: 700px;
        color: #faaf00;
        font-size: 15px;
    }
    .movie_body .btn_mail{
        width: 47px;
        height: 27px;
        line-height: 28px;
        text-align: center;
        background: #f03d37;
        border-radius: 4px;
        font-size: 12px;
        cursor: pointer;
        margin-right: 5px;
    } 
</style>