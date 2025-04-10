## 版本更新记录

### 【1.4.0】2021-05-10

- 升级 `JustAuth` 版本：1.16.1，新增Amazon、Slack、LINE、Okta、钉钉账号登录，同时修复若干BUG，详细信息请参考参考：https://github.com/justauth/JustAuth/blob/master/CHANGELOGS.md#1161
- 升级 `hutool-core` 版本：5.6.5

### 【1.3.5】2021-01-04

- 升级 `JustAuth` 版本：1.15.9，新增飞书、京东、阿里云、喜马拉雅、企业微信网页端登录
- 升级 `hutool-core` 版本：5.5.6

### 【1.3.4】2020-09-12

- 升级 `JustAuth` 版本：1.15.7，更新最新的 GitHub API

### 【1.3.4.beta】2020-08-29

- 升级 `JustAuth` 版本：1.15.7-beta.3，支持自定义 http config 以及自定义 scopes
- 升级 `hutool-core` 版本：5.4.0，修复 `JSONUtil.toJsonStr(obj)` 报错的问题，参见 [ISSUE#8](https://github.com/justauth/justauth-spring-boot-starter/issues/8)

### 【1.3.3】2020-04-13

- 升级 `JustAuth` 版本：1.15.1

### 【1.3.2】2019-12-25

- 升级 `JustAuth` 版本：1.13.2，新增微信公众号登录，区分之前的开放平台登录

### 【1.3.1】2019-11-12

- 升级 `JustAuth` 版本：1.13.1，修复 `AuthCallback` 异常的问题，参见 [ISSUE#52](https://github.com/justauth/JustAuth/issues/52)

### 【1.3.0】2019-11-04

- 修改 `groupId` 为 `com.xkcoding.justauth`
- 升级 `JustAuth` 版本：1.13.0，支持 `推特`

### 【1.2.1】2019-10-12

- 紧急修复Oauth列表空指针BUG

### 【1.2.0】2019-10-09

- 升级 `JustAuth` 版本：1.12.0，支持 `饿了么`、`美团`
- 新增配置项，支持`自定义第三方平台扩展`
- 规范包结构

### 【1.1.0】2019-09-04

- 升级 `JustAuth` 版本：1.11.0，支持 `GitLab`、`酷家乐`
- 添加内置的 Redis 缓存策略，通过配置项可配，不需要额外实现
- 支持 Redis 缓存自定义缓存前缀、自定义缓存过期时间

### *【1.0.2-SNAPSHOT】2019-08-31*

- 添加内置的 Redis 缓存策略，通过配置项可配，不需要额外实现
- 支持 Redis 缓存自定义缓存前缀、自定义缓存过期时间

### 【1.0.1】2019-08-19

- 升级 `JustAuth` 版本：1.10.1，AuthUser添加构造函数，支持反序列化

### 【1.0.0】2019-08-08

- 升级 `JustAuth` 版本：1.10.0，支持 `华为登录`、`企业微信登录`，`自定义State缓存`

### 【0.0.2】2019-08-01

- 升级 `JustAuth` 版本：1.9.5

### 【0.0.1】2019-07-23

- 使用 `JustAuth` 版本：1.9.2

