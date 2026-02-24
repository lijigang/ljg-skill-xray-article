# ljg-skill-xray-article

文章 X-Ray — 一个 [Claude Code](https://docs.anthropic.com/en/docs/claude-code) Skill，透视文章的真问题，检测与你的认知碰撞。

## 功能

- 支持 URL 或粘贴全文输入
- 加载个人认知参照系（soul.md + memory.md），输出锚定到你
- 两件事：文章说了什么（真问题 → 真回答 → 论证骨架）+ 对我意味着什么（认知碰撞卡片）
- 诚实原则：没有碰撞就说没有，不硬凑
- 生成 Org-mode 格式报告，含 ASCII 论证拓扑图和认知碰撞卡片

## 安装

```bash
/install lijigang/ljg-skill-xray-article
```

## 使用

```
/ljg-xray-article <文章URL或粘贴文章内容>
```

## 输出示例

生成的 Org-mode 报告包含：

- **文章说了什么** — 真问题、真回答、论证骨架、隐含假设、边界、ASCII 论证拓扑图
- **对我意味着什么** — 认知碰撞卡片（ASCII art，空间关系本身在说话）
- **迁移** — 仅当洞见的生成规则在另一领域同构时才写

## 设计原则

- 两件事，仅两件：说了什么 + 对我意味什么
- 碰撞检测器，不是填格子机器
- 真问题 != 表面问题：如果提取的问题 = 标题改写，重新挖
- 迁移不预设领域，由洞见形状决定去向

## License

MIT
