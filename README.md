# WeChat Steps API

<details>
  <summary>Please click to view the important tips before use.</summary>

## 免责声明

1. 在使用WeChat Steps API服务时，用户不得以任何方式侵犯他人的合法权益。
2. 本服务不对用户在使用过程中可能发生的数据泄露负责。
3. 用户应合法合规使用本服务，不得用于任何非法活动。
4. 我们不对用户因违反微信平台规定而导致的后果负责。
5. 任何非法或滥用本API所产生的后果将由用户自行承担。
6. 本API可能在未经通知的情况下进行更新或修改，恕不另行通知。
7. 用户需妥善保管API密钥，不得将其透露给他人，一切后果由用户自行负责。
8. 我们不对用户在使用本服务时可能遭受的任何健康问题负责。
9. 请在合法合规的范围内使用本服务，切勿滥用或用于违法活动。
10. 使用本服务即表示用户同意遵守微信平台及相关法规，一切后果由用户自行承担。

免责声明的任何更改将通过本页面发布，用户应定期查看以获取最新信息。

免责声明的效力范围将覆盖使用WeChat Steps API服务的所有用户，包括匿名用户。

本服务可能在未经通知的情况下进行更新或修改，恕不另行通知。

本服务的所有权归开发者所有，未经许可不得进行反向工程或逆向分析。

对于由于不可抗力因素导致的服务中断，我们不承担任何责任。

请不要滥用本服务，以免影响其他用户的正常使用。

用户在使用WeChat Steps API服务时，应保持合理谨慎，自行承担风险，对于因使用本服务而导致的一切后果负责。

如果您对本免责声明有任何疑问，请[邮件](mailto:info@030101.xyz)联系。将尽全力为您提供必要的协助和解释。

**在使用本服务前务必审慎阅读并理解本免责声明的全部内容，使用本服务将被视为对本免责声明的接受和遵守。**

</details>

该项目是一个用于修改微信运动步数的 API，通过操作小米运动（Zepp Life）实现步数修改，并将步数同步至微信运动。

## 交流群和通知频道

- 群聊: [HeroCore](https://t.me/HeroCore)
- 频道: [HeroMsg](https://t.me/HeroMsg)

## Dashboard：

您可以访问 [Dashboard](https://steps.api.030101.xyz/dash) 通过输入账号和密码直观地修改步数，并实时查看修改结果。

<img width="1476" alt="image" src="https://github.com/ymyuuu/Steps-API/assets/135582157/14ddab0f-1664-44f9-85ab-008ba7cbe4ce">

## Help Documents：

```plaintext
https://steps.api.030101.xyz/api?account=账号&password=密码&steps=步数
```
如果 <code>steps</code> 参数为问号（<code>steps=?</code>），系统将自动生成随机步数（30000 到 80000 之间）。

## 使用条件：

1. 下载 [Zepp Life](https://apps.apple.com/cn/app/zepp-life-%E5%8E%9F%E5%B0%8F%E7%B1%B3%E8%BF%90%E5%8A%A8/id938688461)（iOS为例）并注册小米运动（Zepp Life）。
2. 在微信中启用微信运动功能。进入微信点击顶部搜索栏，输入"微信运动"，然后进行开启。
3. 在 Zepp Life 中将账户与微信运动绑定。进入 Zepp Life 点击"我的"，选择"第三方接入"，点击"微信"，最后扫码完成绑定。

## 许可证

本项目采用 MIT 许可证。详细信息请参阅 [LICENSE](LICENSE) 文件。

感谢你的使用！如果你对这个项目有任何改进或建议，也欢迎贡献代码或提出问题。
