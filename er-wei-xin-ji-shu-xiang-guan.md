# 二、微信技术相关

!\[\]\(http://heywoods-down.oss-cn-shenzhen.aliyuncs.com/wdwz/xhw.jpg\)

\#\#\#微信技术相关



&lt;/br&gt;





\#\#\#\#玩家进入游戏的怎么知道是从哪个公众号进去？



&lt;/br&gt;





\* 小程序内部生命周期里可以取到scene值（onLaunch里面的opt），然后取对应的referid

 

&lt;/br&gt;



  



\#\#\#\#小程序的openid和公众号的可以打通吗？



&lt;/br&gt;





\* Union ID可以，但是Open ID不行，Open ID是先各自独立，当用户发生流动的时候再逐步进行关联整合



&lt;/br&gt;





\#\#\#\#Union ID和 Open ID分别是什么？



&lt;/br&gt;





\* 微信用户都有一个唯一的Union ID，你可以理解为用户微信ID，也就是用户在微信上唯一独立的一个编号



\* Open ID这是小程序或小游戏的一个用户ID，每个小程序或者小游戏每个用户都是针对独立的，各自独立



\* Open ID是不同产品，同一个用户针对每个产品都有各自独立唯一永久的Open ID，Union ID不涉及小程序，他就是唯一的用户微信ID，你可以理解为就是微信账号的ID       



&lt;/br&gt;





\#\#\#\#Union ID可以获取到吗？



&lt;/br&gt;





\* Union ID在小程序授权登录的情况下是可以获取的



\* 关注自身运营的公众号用户也可以通过公众号获取   



