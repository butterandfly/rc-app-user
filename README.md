# \<rc-app-user\> [![Build Status](https://travis-ci.org/butterandfly/rc-app-user.svg?branch=master)](https://travis-ci.org/butterandfly/rc-app-user)

一个全局的用户元素。

## 安装

确保你已经安装npm及bower，然后使用bower来安装：

```
bower install butterandfly/rc-app-user
```

## 使用
`user-copy`属性来得到当前用户的copy（注意这是一个克隆，修改该克隆不会同步到全局）：

```html
<rc-app-user id="appUser" user-copy="{{user}}">
</rc-app-user>
```

`setUser`方法来设置当前用户（全局同步）：

```js
this.$.appUser.setUser(this.user);
```
