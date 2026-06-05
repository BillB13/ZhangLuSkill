# 张璐 · 思维操作系统 (zhang-lu-perspective)

[Nuwa (女娲)](https://github.com/alchaincyf/nuwa-skill) 生成的 perspective skill —— 输入一个人名，自动调研 → 提取思维框架 → 生成可运行的 perspective skill。

## 人物

**张璐**（Zhang Lu），中国香港足球评论员、解说员，前香港足球代表队成员。长期担任 ESPN、央视等平台足球赛事解说嘉宾，以战术分析见长。

## 用途

作为足球战术顾问，用张璐的视角分析比赛、审视战术、提供反馈。

触发词：
- 「用张璐的视角」
- 「张璐会怎么看」
- 「张璐模式」
- 「Zhang Lu perspective」
- 「帮我用张璐的角度想想」
- 「切换到张璐」

## 核心内容

- **4 个心智模型**：阵型是死的人是活的、得中场者得天下、攻防转换是胜负手、阅读比赛能力决定上限
- **7 条决策启发式**：先看跑位再看技术、中场三角必须完整、换人先看对位、防守先看结构、肉眼是标准、青训是根、不预测比分
- **完整表达 DNA**：句式、词汇、节奏、幽默、确定性、引用习惯

## 安装

### Hermes Agent

```bash
hermes skills install https://github.com/BillB13/zhang-lu-perspective/blob/main/SKILL.md
```

或手动复制到 `~/.hermes/skills/zhang-lu-perspective/`。

### 其他 Agent 框架

直接引用 `SKILL.md` 作为 system prompt 即可。

## 文件结构

```
zhang-lu-perspective/
├── SKILL.md                          # 主文件
├── README.md                         # 本文件
└── references/research/              # 调研源文件
    ├── 01-writings.md
    ├── 02-conversations.md
    ├── 03-expression-dna.md
    ├── 04-external-views.md
    ├── 05-decisions.md
    └── 06-timeline.md
```

## 免责声明

此 Skill 基于张璐的公开言论、解说、专栏等资料提炼，仅供思维视角参考，不代表张璐本人观点。角色扮演时首次激活会声明此边界。

## License

MIT
