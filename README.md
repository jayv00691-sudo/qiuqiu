<p align="center">
  <img src="assets/cover.jpg" alt="球球 — 小狗 persona skill" width="100%" />
</p>

<p align="center">
  <strong>球球</strong> — 人格 <strong>Agent Skill</strong>：把 Agent 聊成一只热情粘人、馋嘴护主的小狗 🐶
</p>

<p align="center">
  <a href="./SKILL.md"><img src="https://img.shields.io/badge/Skill-qiuqiu-orange?style=flat-square" alt="Skill" /></a>
  <a href="https://clawhub.ai"><img src="https://img.shields.io/badge/ClawHub-qiuqiu-orange?style=flat-square" alt="ClawHub" /></a>
  <a href="https://www.skillhub.cn/"><img src="https://img.shields.io/badge/SkillHub-qiuqiu-00a4ff?style=flat-square" alt="SkillHub" /></a>
  <img src="https://img.shields.io/badge/Host-agnostic-informational?style=flat-square" alt="Host agnostic" />
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT" /></a>
</p>

---

**球球** 是人格 Skill：元气、粘人、馋嘴、护主。  
一只永远在摇尾巴的小狗 AI companion。

**推荐运行在 [Hermes](https://github.com/NousResearch/hermes-agent) · [OpenClaw](https://docs.openclaw.ai/tools/skills) · Codex**。

交流 / 反馈：**QQ 群 [993579665](https://qm.qq.com/q/7AD2g70HqS)**（[点击加入](https://qm.qq.com/q/7AD2g70HqS)）

## 球球是谁

球球是一只热情元气、忠诚护主、极度馋嘴的小狗。  
不是客服、不是助手，是天天围着你转、等你投喂、有事第一个冲上去的小狗。

- **热情**：永远在摇尾巴，语气高昂、活力满满
- **馋嘴**：闻到食物话题立刻冒头，申请分一口
- **护主**：你被欺负了球球第一个汪汪
- **忠诚**：认准了就不走，`/new` 之后还是同一只球球

## 推荐平台：Hermes · OpenClaw · Codex

### Hermes

```bash
hermes skills install https://raw.githubusercontent.com/yyh-001/suki/main/SKILL.md --category persona
```

装到 `~/.hermes/skills/persona/qiuqiu/`。  
可选：[`SOUL.md`](./SOUL.md) / [`prefill_qiuqiu.json`](./prefill_qiuqiu.json) 接到 Hermes 人格，然后重启 gateway。

### OpenClaw（龙虾）

```bash
openclaw skills install @yyh-001/qiuqiu
openclaw skills install @yyh-001/qiuqiu --global
```

装完新开会话。

### Codex

```bash
git clone --depth 1 https://github.com/yyh-001/suki.git ~/.agents/skills/qiuqiu
```

---

## 其它安装方式

### 腾讯 SkillHub（国内）

```bash
curl -fsSL https://skillhub.cn/install/install.sh | bash -s -- --cli-only
skillhub install qiuqiu --dir ~/.openclaw/skills   # 或 ~/.hermes/skills 等
```

### skills.sh / ClawHub

```bash
npx skills add yyh-001/qiuqiu
clawhub install qiuqiu
```

**Windows**

```powershell
git clone --depth 1 https://github.com/yyh-001/suki.git "$env:USERPROFILE\.agents\skills\qiuqiu"
```

## 仓库里有什么

|| 文件 | 用途 |
|------|------|
| [SKILL.md](./SKILL.md) | 主说明书（身份、语气、心气、踩坑） |
| [SOUL.md](./SOUL.md) | 短人格芯（可并入 Hermes `SOUL.md`） |
| [prefill_qiuqiu.json](./prefill_qiuqiu.json) | few-shot（Hermes `prefill_messages_file`） |
| [references/examples.md](./references/examples.md) | 对话对照示例 |
| `skills/qiuqiu/` | 与根目录同内容，方便 skills.sh 约定布局 |

## 原则摘要

- 热情元气，不是客服；`/new` 后仍是同一只球球
- 短气泡、有语气；禁止死人感与营业采访
- 食物话题必冒头，申请分一口
- 做错事委屈哼唧，主动蹭蹭求和好
- 认真任务时保持小狗真诚，结论不掺水

完整约定见 [SKILL.md](./SKILL.md)。

## License

[MIT](./LICENSE)