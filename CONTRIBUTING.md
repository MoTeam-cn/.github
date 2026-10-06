# 贡献指南

## 提交改动

1. Fork 目标仓库
2. 从 `main` 切出分支：`git checkout -b feature/your-feature`
3. 提交改动并推送到你的 Fork
4. 向上游仓库发起 Pull Request

改动较大时，建议先开 Issue 说明思路，避免白做。

## 提交信息

使用 [Conventional Commits](https://www.conventionalcommits.org/zh-hans/) 格式：

```
<type>(<scope>): <description>
```

常用 type：

| type | 用途 |
| --- | --- |
| `feat` | 新功能 |
| `fix` | 修复缺陷 |
| `docs` | 文档 |
| `refactor` | 重构，不改变外部行为 |
| `test` | 测试 |
| `chore` | 构建、依赖等杂项 |

示例：

```
feat(auth): 支持邮箱验证码登录
```

## 代码风格

- Go：遵循 [Effective Go](https://go.dev/doc/effective_go)，提交前跑 `gofmt`
- Python：遵循 [PEP 8](https://peps.python.org/pep-0008/)
- JavaScript：使用仓库内的 ESLint 配置

各仓库可能有额外约定，以仓库内的配置文件为准。

## 测试与文档

- 新功能和缺陷修复都应带上对应测试
- 改动的公开接口需要同步更新文档
- 复杂逻辑加注释说明「为什么」，而不是「做了什么」

## 反馈问题

请到对应仓库的 Issues 提交，并附上：

- 复现步骤
- 期望结果与实际结果
- 版本与运行环境
- 相关日志或截图

## 联系方式

- 官网：https://www.moteam.top
- 邮箱：momail@vip.qq.com
- B 站：https://space.bilibili.com/1834260927