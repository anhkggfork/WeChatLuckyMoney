WeChatLuckyMoney
=
## 更新于2016.12.9 
#### 测试：微信版本：6.3.31，手机型号：华为p8， android版本：23
        网上有很多抢红包工具的代码解析，但基本全部是基于通知的。我对通知没有好感，所以我的群都是设置为消息免打扰模式，<br/>
        这就导致了红包工具在我这基本失灵。所以只能自己动手，研究了一下代码，又顺便研究了下AccessibilityService这个类，<br/>
        然后就搞出了现在的东西。这个工具可以使用通知也可以关闭通知，但是关闭通知必须保证屏幕亮着并且在微信主页或者群聊天页面才可以。

#### 当前问题
    在聊天界面，如果是最后一条聊天消息，会不断重复打开关闭操作

### 主要功能
* 可以通过通知进入程序抢
* 可以在微信主页面监控"[微信红包]"进入聊天页面抢
* 可以在聊天页面直接抢
* 抢完之后会返回到聊天页面

###