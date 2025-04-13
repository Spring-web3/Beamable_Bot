# Beamable_Bot



## Beamable项目介绍
Beamable 是一个开放的、可扩展的游戏服务器平台，可让用户在几分钟内创建在线游戏和虚拟世界。通过去中心化物理基础设施网络，Beamable 旨在改变游戏后端基础设施的构建和运营方式。

## Beamable融资信息
![image](https://github.com/user-attachments/assets/ca838514-bad8-493a-a417-ae95fbbdbefc)

## 脚本功能

![image](https://github.com/user-attachments/assets/4c9bef59-0923-445a-be8a-f3c7cf550a39)


日常签到:需要每天执行，领取一个宝箱。

积分兑换宝箱:把之前做任务获得的points兑换为BNB Creds。

领取WalletActivated徽章:领取钱包认证徽章。

打开账号全部宝箱:打开目前获得的全部箱子。签到一段时间后感觉数量多了可以开启一遍。
## 辅助脚本使用教程

Beamable活动地址 :https://hub.beamable.network/modules/rewards

由于易语言的不可跨平台性，软件只支持windows环境运行，防火墙和杀毒软件对易语言编译的软件经常误报，可以忽略。长期使用建议挂在海外云服务器，有每日任务之类的可以长期挂机。 首次使用请将spring.exe放在C盘根目录，这是后续每个软件需要用到的nodejs后端接口服务。 请将RSCProject.dll和BeamableBot.exe放置在同一目录下，Beamable.exe有用到RSCProject.dll的支持库配置。 软件为免费提供分享，卡密key:

```
2106aca2-e26d-4d60-8d61-2b51ad9bb30a
```



卡密key会不定时更新，请关注X和TG获取最新卡密信息。 软件免费分享，不开源，如果有顾虑的小伙伴请不要选择使用。信任的朋友也请使用不常用的无余额撸毛钱包和小余额钱包。 钱包安全由自己负责，本软件不承担任何责任。也欢迎任何技术大佬抓包反编译检测软件是否包含恶意程序。

本次程序不涉及导入钱包，只需要导入登录凭证即可。因为前期已经写过此软件全自动流程，后期项目方进行了更新，所以此次版本重写后只提供了任务模块功能，注册的话还请大家手动注册。

下面是提取Beamable登录令牌的教程:

打开活动网址，在浏览器打开F12开发者工具，点击Application标签页，点击Storage里面的Cookies选项，找到活动网址单击，如图把harbor-session提取出来整理到一个txt文本当中，多条session以换行符分割，大白话就是一行一个。
![image](https://github.com/user-attachments/assets/2a7b4350-a789-45a9-a4cc-5d8129490468)



之前经常参与这个项目的小伙伴也知道手动做任务时经常遇到网站返回403的错误，是因为这个项目方对用户IP的校验特别严格，很多节点是无法通过他的IP验证的，所以使用软件时要搭配代理IP来解决这个问题。此次软件需要是用账号密码格式的代理。代理一定要设置为**轮询格式**。

代理格式需要设置为 : username:password@hostname:port

基本所有的代理网站都支持生成这个格式的。有的代理网站提供的代理可能无法通过。优先选择动态住宅代理。质量和性价比可以得到兼顾。

获得代理后请把代理放入软件的代理设置标签页里面的账号密码代理编辑框内。

给没有代理的朋友分享一个:

https://app.nstproxy.com/register?i=EqNcle

选择1.8刀/G的通道使用即可。

nstproxy的轮询选择方式为:

![image](https://github.com/user-attachments/assets/71f84867-e094-4108-b1d3-9efae2c2fb0b)
