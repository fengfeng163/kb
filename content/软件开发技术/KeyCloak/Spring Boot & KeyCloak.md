 怎么使用springboot集成keycloak实现单点登录功能
https://www.bilibili.com/video/BV1t44y1K74W/


application.properties

```
keycloak.realm = UniHeart
keycloak.auth-server-url = https://keycloak.jiwai.win/auth
keycloak.ssl-required = externalkeycloak.resource = demoapp
keycloak.use-resource-role-mappings = true
keycloak.public-client=true
keycloak.security-constraints[o].authRoles[o]=visitor
keycloak.security-constraints[e].securityCollections [e].patterns[e]=/visitor/*
```
DemoApplicationTests.java
![[Pasted image 20260701230235.png]]