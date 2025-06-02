# 贡献指南

感谢您考虑为 MoTeam 做出贡献！以下是一些指导原则，帮助您参与我们的项目。

## 如何贡献

1. Fork 项目
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 提交规范

我们使用 [Conventional Commits](https://www.conventionalcommits.org/) 规范，提交信息格式如下：

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

### 类型 (type)

- `feat`: 新功能
- `fix`: 修复
- `docs`: 文档更改
- `style`: 代码格式修改
- `refactor`: 代码重构
- `test`: 测试用例修改
- `chore`: 其他修改

### 示例

```
feat(auth): 添加用户登录功能

- 实现用户名密码登录
- 添加 JWT 认证
- 增加登录页面
```

## 开发流程

1. 请先查看 [Issues](https://github.com/MoTeam-cn/issues) 列表
2. 如果您想处理某个 issue，请先评论说明
3. 开发完成后提交 PR
4. 等待审核和合并

## 代码风格

- Go 代码遵循 [Go 官方规范](https://golang.org/doc/effective_go)
- Python 代码遵循 [PEP 8](https://www.python.org/dev/peps/pep-0008/)
- JavaScript 代码使用 ESLint 标准配置

## 测试要求

- 所有新功能必须包含测试用例
- 所有修复必须包含相关的测试用例
- 测试覆盖率不得降低

## 文档要求

- 新功能需要更新相关文档
- 更新 API 时需要更新对应的 API 文档
- 重要的代码需要添加注释

## 问题反馈

- 使用 GitHub Issues 提交问题
- 清晰地描述问题
- 提供复现步骤
- 附上相关的日志或截图

## 联系我们

- 网站：https://www.moteam.top
- 邮箱：momail@vip.qq.com
- B站：https://space.bilibili.com/1834260927

感谢您的贡献！ 