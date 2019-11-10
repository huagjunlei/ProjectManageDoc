# OAuth2.0

官网网站：https://oauth.net/2/

## 令牌与密码

令牌（token）与密码（password）的作用是一样的，都可以进入系统，但是有三点差异。

* 时限不同：令牌是短期的，到期会自动失效，用户自己无法修改。密码一般长期有效，用户不修改，就不会发生变化。
* 可撤销性：令牌可以被数据所有者撤销，会立即失效。以密码一般不允许被他人撤销。
* 授权范围：令牌有权限范围（scope）。对于网络服务来说，只读令牌就比读写令牌更安全。密码一般是完整权限。

https://blog.csdn.net/qq_34190023/article/details/82629092