# Hermes 开发工作流 🧠

Spike → Plan → Execute → Debug → Recover 五阶段开发心智模型。

| 阶段 | 做什么 | 核心原则 |
|------|--------|----------|
| Spike | 快速验证想法 | 用完就扔 |
| Plan | 写执行计划 | 2-5分钟任务粒度 |
| Execute | 子Agent执行 | 两阶段审查 |
| Debug | 根因调试 | 不找到根因不写修复 |
| Recover | 失败重试 | 最多1次 |

## 安装
```bash
git clone https://github.com/remix2111/hermagent-dev-workflow.git
cp -r hermagent-dev-workflow/skills/hermes-dev-workflow ~/.hermes/skills/
```

## 使用
/skill hermes-dev-workflow

## License
MIT