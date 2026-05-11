# 安装指南 / Installation Guide

## Claude Code

### 方式一：手动复制

```bash
# 克隆仓库
git clone https://github.com/your-username/best-skills-research-writing.git

# 复制 skills 到 Claude Code 目录
cp -r best-skills-research-writing/skills/* ~/.claude/skills/
```

### 方式二：使用 OpenSkills

```bash
npx openskills install your-username/best-skills-research-writing
```

## Cursor

Skills 会自动从以下目录发现：
- `.claude/skills/`
- `.cursor/skills/`

复制 skills 到任一目录即可。

## Codex

```bash
# 创建目录（如果不存在）
mkdir -p ~/.codex/skills

# 复制 skills
cp -r best-skills-research-writing/skills/* ~/.codex/skills/
```

## 验证安装

安装后，重启 Claude Code / Cursor / Codex，然后输入 `/` 查看可用的 skills。

## 卸载

```bash
# 删除已安装的 skills
rm -rf ~/.claude/skills/idea-discovery
rm -rf ~/.claude/skills/literature-review
rm -rf ~/.claude/skills/research-gap
rm -rf ~/.claude/skills/paper-writing
rm -rf ~/.claude/skills/de-ai
rm -rf ~/.claude/skills/paper-review
rm -rf ~/.claude/skills/rebuttal
```

## 常见问题

### Q: Skills 没有出现？

A: 确保 skills 目录结构正确：
```
~/.claude/skills/
├── idea-discovery/
│   └── SKILL.md
├── literature-review/
│   └── SKILL.md
├── ...
```

每个 skill 必须是一个文件夹，里面包含 `SKILL.md` 文件。

### Q: 如何更新 skills？

A: 重新克隆仓库并复制即可：
```bash
cd best-skills-research-writing
git pull
cp -r skills/* ~/.claude/skills/
```

### Q: 可以只安装部分 skills 吗？

A: 可以。只复制你需要的 skill 文件夹即可。
