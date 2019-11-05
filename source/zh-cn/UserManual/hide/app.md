title: 什么是绑定其它产品的应用
---
# 定义
绑定其它产品的应用是为了实现一个App可以控制多款产品的需求而必须进行的操作。

# 详细说明
在App开发过程，机智云会为您的产品分配的一个独立用户系统。在“应用配置”页面创建的App ID都是指向该用户系统。你只需要把iOS和Android的App ID分别写进去对应平台的App里，这样就可以实现在iOS登录的账号也可以在Android登录。

上面的方法在一个产品对应一个App时是没问题，但是，有些客户厂商不止生产一款产品，他们希望生产的所有产品都可以使用同一个App进行控制。这种一个App控制多个产品的App我们称之为超级App。想实现超级App的方法就是让不同的产品的用户系统都指向同一个，也就是“绑定其它产品的应用”这个功能。选定其中一个产品的用户系统作为中心，其它产品去绑定它，再把作为中心产品的App ID写到对应平台的App里就完成了。

# 操作说明
应用配置增加了一个高级功能——「绑定其它产品的应用」，主要满足部分厂商一个App控制旗下多个设备的需求。

例如以下场景：
例如公司Q有多个产品，分别是A、B、C，但他不想每个产品都单独一个App，而是希望三个产品都用同一个app。现在提供了「绑定其它产品的应用」功能，选择其中一个为中心，如产品A为中心，产品B与产品C绑定产品A，开发App时使用产品A的App ID就行。

具体操作如下：
第一步：点击“高级”选择“绑定其它产品的应用”
![输入图片说明](http://dev.gizwits.com/generated/attach/%E9%AB%98%E7%BA%A7.png)

第二步：选择要绑定的产品
![输入图片说明](http://dev.gizwits.com/generated/attach/%E9%80%89%E6%8B%A9%E7%BB%91%E5%AE%9A%E5%88%97%E8%A1%A8.png)


第三步：看到绑定的后的效果
![输入图片说明](http://dev.gizwits.com/generated/attach/%E7%BB%91%E5%AE%9A%E5%90%8E.png "在这里输入图片标题")


期待您向我们反馈对于本次新功能的感受：http://cn.mikecrm.com/3RkhIv7