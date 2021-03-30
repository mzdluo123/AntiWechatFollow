# AntiWechatFollow
讨厌了关注微信查看更多，看这里吧！

本项目的目的只是为了让更多人能够更加方便的阅读文章，觉得作者的文章不错请记得关注作者的公众号来鼓励作者

目前收集到的样本太少，暂时无法实现通杀脚本，以下是部分已经解决的网站。PR Welcome!

## http://woshicver.com/ - OpenCV官方中文文档

打开开发人员工具，屏蔽以下请求

```
woshicver.com/js/readmore2.js
woshicver.com/js/readmore.js
```

## https://www.iocoder.cn/ - 芋道源码 —— 纯源码解析博客

打开开发人员工具，输入以下代码并刷新

```
 $.cookie(cookie_vip_key, cookie_vip_val, {
                                expires: 30,
                                path: '/'
                            });
```
