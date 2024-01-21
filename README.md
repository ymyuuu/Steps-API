# WeChat Steps API

该项目是一个用于修改微信运动步数的 API，通过操作小米运动（Zepp Life）实现步数修改，并将步数同步至微信运动。

<img width="1459" alt="image" src="https://github.com/ymyuuu/Steps-API/assets/135582157/0e3476b6-a3b2-4585-a141-7f97c26db7d7">



## 交流群和通知频道

欢迎加入我们的交流群 [Preferred IP Push Chat](https://t.me/Preferred_IP_Push_Chat)

同时，你可以关注我们的通知频道 [Preferred IP Push](https://t.me/Preferred_IP_Push)

## 如何使用：

```plaintext
https://steps.api.030101.xyz/api?account=账号&password=密码&steps=步数
```
如果 <code>steps</code> 参数为问号（<code>steps=?</code>），系统将自动生成随机步数（30000 到 80000 之间）。

## 实现原理：

通过与小米运动（Zepp Life）进行互动，模拟用户真实步数的生成过程，并将这些虚拟步数同步至微信运动。

## 使用条件：

1. [下载 Zepp Life](https://apps.apple.com/cn/app/zepp-life-%E5%8E%9F%E5%B0%8F%E7%B1%B3%E8%BF%90%E5%8A%A8/id938688461) 并注册小米运动。
2. 在微信中启用微信运动功能。
3. 在 Zepp Life 中将账户与微信运动绑定。

## 免责声明：

1. 本项目仅供学习和研究之用，严禁将其用于任何非法用途。
2. 使用该 API 可能导致微信运动账户异常，作者对此不承担任何责任。
3. 由于使用本 API 导致的数据丢失或其他损害，作者概不负责。
4. 请在遵守法律法规的前提下使用本 API，任何违法行为与本项目无关。
5. 作者保留随时更改免责声明和项目条款的权利，敬请关注最新公告。

## 许可证

本项目采用 MIT 许可证。详细信息请参阅 [LICENSE](LICENSE) 文件。

感谢你的使用！如果你对这个项目有任何改进或建议，也欢迎贡献代码或提出问题。
