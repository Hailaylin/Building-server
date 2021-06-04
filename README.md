# MilkTown Building Server
* 在这里保存配置此服务端的一些信息，仅供参考

## 服务器建立宗旨
* **生存** - 难度稍大
* **真实** - 真实地形等
* **建筑** - 不开放飞行的建筑，雕刻模组等
* **探险** - 暮色打怪之类的
* **稳定** - 24小时开放
* **流畅** - 延迟100ms内，tps>18

## 服务器部署
* 测试地址暂时为 127.0.0.1:25565
* 外网连接地址暂定为 hz.hailay.site:25570
* 待在月姬测试完成后部署到丹姬 ``D:\mc\je\Building-server\``
* 使用``mcsm``统一管理丹姬的所有Minecraft服务端
* 使用本地数据库，不使用mysql，方便迁移，除非用docker…… 但是要ubuntu才方便docker

## 服务器技术
* 版本 - 1.16.5 ——> 待模组+插件成熟升级1.17
* 采用[arclight](https://github.com/IzzelAliz/Arclight)的解决方案，使得模组和插件能同时使用(这就是某个老师说的，开源的宝贝😂😂)

## 使用的插件

* MOTD ColorMOTD.jar 
  * http://vcheck.windit.net/mc_plugin/andylizi/colormotd/website/index.html
  * https://www.mcbbs.net/thread-448326-1-1.html

* 登录 AuthMe-5.6.0-SNAPSHOT.jar
  * [管理|安全][PCD]AuthMeReloaded —— 高效稳定的老牌登录插件[1.5-1.16.X]
https://www.mcbbs.net/thread-442729-1-1.html
(出处: Minecraft(我的世界)中文论坛)

* 基础插件 EssentialsX
  * https://github.com/EssentialsX/Essentials/releases
  * [综合|经济|传送|管理][少更新]Essentials EssentialsX —— 基础插件[1.7.10-?]
https://www.mcbbs.net/thread-619883-1-1.html
(出处: Minecraft(我的世界)中文论坛)

*  
## 使用的模组
* 建筑 [雕刻]chiselsandbits-0.3.4-RELEASE.jar 