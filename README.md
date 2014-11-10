###综合概述###

一款模拟老虎机形式的抽奖插件
<img src="http://sfault-image.b0.upaiyun.com/958/921/958921584-546089cb791ed_articlex"/>

###兼容性###

IE6+、Chrome、Firefox、Safari、Opera

###框架依赖###

依赖框架：jQuery

###模块支持###

支持AMD、node和浏览器

###使用介绍###
1.HTML页面结构

ps:一般抽奖类的机构，基本都是由列表或者table组成。不过推荐列表的形式最佳。本插件是根据列表形式来修改的。
    
    //可以参考demo中的示例
    <div class="inbox">
            <ul id="random_box">
                <li id="random_1">谢谢惠顾</li>
                <li id="random_2">苹果笔记本</li>
                <li id="random_3">谢谢惠顾</li>
                <li id="random_4">10Q币</li>
                <li id="random_5">谢谢惠顾</li>
                <li id="random_6">5Q币</li>
                <li id="random_7">谢谢惠顾</li>
                <li id="random_8">5Q币</li>
                <li id="random_9">谢谢惠顾</li>
                <li id="random_10">10Q币</li>
                <li id="random_11">谢谢惠顾</li>
                <li id="random_12">5Q币</li>
                <li id="random_13">谢谢惠顾</li>
                <li id="random_14">5Q币</li>
            </ul>
            <b class="ok" id="ok">抽奖</b>
     </div>
     
2.css的结构由于会根据UI的改变而发生改变，所以样式结构不固定，但是要放到指定的结构中去。

3.添加脚本,更多参数请参阅源代码，或在github上留言。
    
    //先new出来一个对象
    var raffle = new $.Raffle({
        succCB : function(){
            alert("成功后的回调函数");
        }
    });
    //调用
    raffleinit()

###下载连接###

https://github.com/hehongwei44/raffle

###授权信息###

授权类型：MIT

授权类型信息：https://github.com/hehongwei44/raffle/blob/master/LICENSE

###更改日志###

https://github.com/hehongwei44/raffle/blob/master/ChangeLog.md

###其他补充###

我们可能会遇到这样的需求、遇到各种什么节日的话，就会举办抽奖类的活动，用来吸引用户参加。
那么产品那边希望开发能写出酷炫叼炸天特效来提高用户体验，这个插件，虽然不能说很经验，但是
足以应付常见的需求，如果遇到其他插件没有的功能，可以修改源码以添加新的需求。



