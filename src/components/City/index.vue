<template>
    <div class="city_body">
        <div class="city_list">
              <div class="city_hot">
            <h2>热门城市</h2>
            <ul class="clearfix">
                <li>北京</li>
                <li>深圳</li>
                <li>广州</li>
                <li>西安</li>
                <li>厦门</li>
            </ul>
        </div>
        <div class="city_sort">
            <div>
                <h2>A</h2>
                <ul>
                    <li>安康</li>
                    <li>安庆</li>
                    <li>安徽</li>
                </ul>
            </div>

              <div>
                <h2>B</h2>
                <ul>
                    <li>北京</li>
                    <li>宝鸡</li>
                    <li>包头</li>
                </ul>
            </div>

              <div>
                <h2>C</h2>
                <ul>
                    <li>重庆</li>
                    <li>昌吉</li>
                    <li>昌平</li>
                </ul>
            </div>

               <div>
                <h2>D</h2>
                <ul>
                    <li>大连</li>
                    <li>大庆</li>
                    <li>大理</li>
                </ul>
            </div>
        </div>
        </div>
       <div class="city_index">
                <ul>
                    <li>A</li>
                    <li>B</li>
                    <li>C</li>
                    <li>D</li>
                    <li>E</li>
                    <li>F</li>
                    <li>G</li>
                    <li>H</li>
                    <li>I</li>
                    <li>G</li>
                    <li>K</li>
                    <li>L</li>
                    <li>M</li>
                    <li>N</li>
                    <li>O</li>
                    <li>P</li>
                    <li>Q</li>
                    
                </ul>
            </div>
    </div>
</template> 

<script>
export default {
    name:'City'
}
</script>


<style  scoped>
.city_body{
    display:flex;
    width:100%;
    position: obsolute;
    top:0;
    bottom: 0;
}
.city_body .city_list{
    flex: 1;
    overflow: auto;
    background: #fff5f0;
}
.city_body .city_list::-webkit-scrollbar{
    width: 0;
    background: transparent; 
}
.city_body .city_hot{
    margin-top: 20px;
}
.city_body .city_hot h2{
    padding-left :15px;
    line-height: 30px;
    font-size :14px;
    background: #f0f0f0;
}
.city_body .city_hot ul li{
    float: left;
    background: #fff;
    width: 29%;
    height: 33px;
    margin-top: 15px;
    margin-left: 3%;
    border: 1px solid #e6e6e6;
    border-radius: 3px;
    text-align: center;
    box-sizing:border-box;
    line-height: 33px;
}
.city_body .city_sort div{
    margin-top: 20px;
}
.city_body .city_sort h2{
    padding-left: 15px;
    line-height: 30px;
    font-size: 14px;
    background: #f0f0f0;
    font-weight: 400;
}
.city_body .city_sort ul {
    margin-top: 10px;
    padding-left: 10px;
}
.city_body .city_sort ul li{
    font-size: 14px;
    line-height: 30px;
}
.city_body .city_index{
    font-size: 10px;
    margin-left: 5px;
    width: 20px;
    display: flex;
    flex-direction: column;
    justify-content: center;
}
</style>