B站学习视频
https://www.bilibili.com/video/BV1334y11739/
作者网站： https://tech.aufomm.com/

Zlib
《実践 Keycloak》
https://zh.z-library.sk/book/yRa1X9e3RQ/%E5%AE%9F%E8%B7%B5-keycloak.html

## Clients设置
### Valid Redirect URIs: 
验证完成后的回调URL。
需要注意回调URL会使用外部IP，验证的时候都是搭建的本地Web应用，用localhost访问的，至少需要看看局域网IP能否访问Web应用。

一般要填写至少两项
1. 外部地址 例：http://xxx.com/*
2. 本地地址 例：http://localhost:8080/*

Original 不填也可以的。


