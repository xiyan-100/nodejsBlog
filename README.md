### 前言
> 1. 参考Nodejs开发指南一书的第5章，受限于书中的nodejs和express版本太低，相当一部分代码在新版本的nodejs和express下都是无法使用
> 2. 感谢[cnodejs社区]
> 3. 目前完成了一个简单微博所应具有的基础功能，后续会对此项目进行优化，完善和补充

### 开发环境
1. 操作系统: OSX Yosemite 10.10.5
2. `nodejs` : v5.1.0
3. `express` : 4.14.0
4. `MongoDB` : 3.2.7
### 项目介绍
#### 1.用户注册
界面如下：
![用户注册](./public/img/reg.png)
#### 2.用户登录
![用户登录](./public/img/login.png)
#### 3.发表微博
![发表微博](./public/img/publish.png)
#### 4.显示微博
![显示微博](./public/img/show.png)
#### 5. 登录密码错误
在注册成功后，尝试登录时，如果密码错误，则提示:
![登录密码错误](./public/img/password-error.png)

#### 6. 权限控制
比如，在未登录的情况下，访问 /logout时，会提示:
![未登录](./public/img/pri.png)

#### 7. 其它功能
