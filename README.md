# USTC-Software 2019 iGEM 后端测试题

## 任务

你需要：

1. Fork 此仓库至你的账号。
2. 使用 Django，完成如下所述的功能。
3. 在本文件末尾为前端组的同学撰写一份说明文档，使他们了解你的应用的接口等信息。
4. 发起 Pull Request。

### 约定

为了节约大家的时间，请尽量使用默认配置的组件：

1. 使用 Python 3.6+ 与 Django 2.2。如果你使用了 Python 3.7 的特性，请在报告中注明。
2. 使用默认的数据库 (SQLite)、默认的 HTTP 服务器和默认的端口。
3. 不需要使用 template，不需要编写 HTML 文件。所有接口的返回内容为 JSON。

## 目标功能

### 必须完成的功能

- 登录账户
- 注册账户
- 退出 (log out) 账户
- 显示与修改账户的个人信息

### 可以选做的功能

- 「给未来的自己发送消息」，分为两个接口：
  - 接口 1: 用户可以输入一条消息与这条消息隐藏的时间。例如，某条消息隐藏时间为 5 分钟，则在用户提交 5 分钟之后，这条消息才能在接口 2 中显示。
  - 接口 2: 显示当前用户未隐藏的消息。
  - 可以在此基础上扩充更多功能。

### 加分项

这些加分项都是值得提倡的良好的开发习惯，因此我们将它们作为加分项。

- 良好的代码风格（如变量命名）会有额外加分
- 良好的文档会有额外加分
- 良好的 Git 提交记录（每次提交有明确的信息）会有额外加分
- 良好的安全性、鲁棒性和可扩展性会有额外加分
- 良好的单元测试有额外加分

## 其它注意事项和提醒

- 对于以上提到的各项功能，最基础的要求是：用户输入正确的请求时，程序可以给出正确的回复。

  你可以选择将这些功能做得更完善和更安全，具体内容和方式请自行决定，例如检查输入并返回有意义的错误信息等。
  
- 你可以参考[去年的后端测试题](https://github.com/volltin/USTC-Software-2018-BE-Test)，但请注意，**不要抄袭其他人的代码**，如果某段代码对你编写有帮助，请在注释中写明来源。

- 允许使用任意 pypi 中的模块，即可以使用 `pip` 命令安装的模块。

- 我们最终的代码会在 Linux 下执行，所以如果你在使用其它操作系统开发，请谨慎使用依赖于特定操作系统的特性。（但这里应该不会出现这种情况）

## 报告（需要完成）

请将你为前端组的同学撰写的报告放在这里。
