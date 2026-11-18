# quality

两项可直接在 Codex 中调用的 Three.js 质量技能，适用于游戏、动画短片、产品演示和可漫游空间。制作人负责交付，独立评审者用成品取证。规则来自 [The Fable Three.js Prompt 原图](https://pbs.twimg.com/media/HXBCAPybcAA2fHd?format=jpg&name=4096x4096)。

| 我想做什么 | 调用 |
| --- | --- |
| 把简报变成五秒试片，做完主视觉和完整流程，准备交付 | [$threejs-production](.agents/skills/threejs-production/SKILL.md) |
| 验收一张图、一支短片或一条可操作的路径，找出最该先修的问题 | [$threejs-critic](.agents/skills/threejs-critic/SKILL.md) |

## 使用

从仓库根目录打开新的 Codex 会话。制作时给出范围、受众和核心动作。例如可以这样开工。

> $threejs-production 为品牌官网做一支 15 秒、16:9 的静音概念短片，让首次观看的买家看懂台灯从折叠到点亮。先给我开工回复和试片安排。

评审时另开一个会话，只交成品、对标和验收条件。下面的调用可以直接用仓库里的样片尝试。

> $threejs-critic 打开 validation/motion-sample.mp4 和 validation/motion-retest.mp4。本轮只验最长连续定格，分别给出判定、起止时间、秒数和下一步。

两项技能共用端到端、属性和差分测试规程，记录实际运行的版本、操作、结果与失败证据。[验证规程](docs/verification.md) · [自测记录](validation/README.md)
