# ljg-skill-xray-article

智慧X光机 (Wisdom X-Ray Scanner) — 一个 [Claude Code](https://docs.anthropic.com/en/docs/claude-code) Skill，用四层漏斗方法论透视文章，提炼可迁移的智慧晶核。

## 功能

- 支持 URL 或粘贴全文输入
- 四层分析：表层扫描 → 深层透视 → 晶核定位 → 智慧拓扑
- 提炼智慧公式（可跨领域迁移）
- 生成 Org-mode 格式报告，含 ASCII 可视化

## 安装

```bash
# 克隆到 Claude Code skills 目录
git clone https://github.com/lijigang/ljg-skill-xray-article.git ~/.claude/skills/ljg-xray-article
```

## 使用

在 Claude Code 中输入：

```
/ljg-xray-article <文章URL或粘贴文章内容>
```

## 输出示例

生成的 Org-mode 报告包含：

- **WISDOM CORE** — 智慧公式
- **LAYER 1-4** — 四层递进分析
- **ARGUMENT TOPOLOGY** — ASCII 论证拓扑图
- **TRANSFER MATRIX** — 跨领域迁移矩阵
- **ACTION PROTOCOL** — 可执行行动清单

## License

MIT
