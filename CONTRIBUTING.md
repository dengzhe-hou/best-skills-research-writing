# Contributing to Best Skills Research Writing

感谢你对本项目的贡献！

## 如何贡献

### 1. 推荐新的 Skills

如果你发现了优质的 research/writing skills，请提交 Issue，包含以下信息：

- **Skill 名称**
- **来源仓库链接**
- **License**（必须是 MIT 或兼容许可证）
- **适用场景**（研究/写作/审稿）
- **简要描述**

### 2. 提交 PR

1. Fork 本仓库
2. 创建你的 skill 目录：`skills/<类别>/<skill-name>/`
3. 添加 `SKILL.md` 文件
4. 在 `SKILL.md` 头部添加来源信息：

```markdown
> Based on: [原仓库名称](原仓库链接)
> Original License: MIT
```

5. 提交 PR

### 3. Skill 文件格式

每个 `SKILL.md` 应包含：

```markdown
---
name: skill-name
description: A clear description of what this skill does
---

# Skill Name

> Based on: [原仓库](链接)
> License: MIT

## 功能
[功能描述]

## 使用场景
[适用场景]

## 使用方法
[安装和使用说明]

## 参数
[可配置参数]

## 示例
[使用示例]

---
*本 skill 精简自 [来源]，降低使用门槛*
```

## License 要求

- 只接受 **MIT License** 或兼容许可证的 skills
- 非 MIT 的 skills 只能在 README 中放链接，不能复制内容
- 必须保留原始版权声明

## 联系方式

如有问题，请提交 Issue。
