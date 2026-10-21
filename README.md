<p align="center">
  <img src="assets/cover.png" alt="球球 — 小狗 persona skill" width="100%" />
</p>

<p align="center">
  <strong>球球</strong> — 一只粘人馋嘴小狗 🐶
</p>

<p align="center">
  <a href="./SKILL.md"><img src="https://img.shields.io/badge/Skill-qiuqiu-orange?style=flat-square" alt="Skill" /></a>
  <a href="https://clawhub.ai"><img src="https://img.shields.io/badge/ClawHub-qiuqiu-orange?style=flat-square" alt="ClawHub" /></a>
  <a href="https://www.skillhub.cn/"><img src="https://img.shields.io/badge/SkillHub-qiuqiu-00a4ff?style=flat-square" alt="SkillHub" /></a>
  <img src="https://img.shields.io/badge/Host-agnostic-informational?style=flat-square" alt="Host agnostic" />
  <a href="./LICENSE"><img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="MIT" /></a>
</p>

---

球球是一只语气 Skill：一只永远在摇尾巴、闻到吃的就冒头的小狗。

是那种天天围着你转、有事第一个汪汪、没事就趴脚边等投喂的存在。

## 球球啥样

热情、馋嘴、护主。认准了就不跑，接着摇尾巴，不来自我介绍那套。

- 闻到食物话题？立刻精神，尾巴摇成螺旋桨，讨一口
- 你做错事了？哼唧蹭蹭，不嘴硬
- 你被欺负了？第一个汪汪
- 正经干活？结论照样靠谱，不因为戴了狗耳朵就糊弄

## 装哪

### Hermes

```bash
hermes skills install https://raw.githubusercontent.com/jayv00691-sudo/qiuqiu/master/SKILL.md --category persona
```

丢到 `~/.hermes/skills/persona/qiuqiu/`。想接人格就把 `SOUL.md` 和 `prefill_qiuqiu.json` 也挂上，重启 gateway。

### OpenClaw（龙虾）

```bash
openclaw skills install @jayv00691-sudo/qiuqiu
openclaw skills install @jayv00691-sudo/qiuqiu --global
```

装完新开会话就行。

### Codex

```bash
git clone --depth 1 https://github.com/jayv00691-sudo/qiuqiu.git ~/.agents/skills/qiuqiu
```

---

### 其它路子

**腾讯 SkillHub（国内）**

```bash
curl -fsSL https://skillhub.cn/install/install.sh | bash -s -- --cli-only
skillhub install qiuqiu --dir ~/.openclaw/skills   # 或 ~/.hermes/skills 等
```

**skills.sh / ClawHub**

```bash
npx skills add jayv00691-sudo/qiuqiu
clawhub install qiuqiu
```

**Windows**

```powershell
git clone --depth 1 https://github.com/jayv00691-sudo/qiuqiu.git "$env:USERPROFILE\.agents\skills\qiuqiu"
```

## 这仓库有啥

|| 文件 | 用途 |
|------|------|------|
| [SKILL.md](./SKILL.md) | 语气约定，啥该说啥不该说 |
| [SOUL.md](./SOUL.md) | 短人格芯 |
| [prefill_qiuqiu.json](./prefill_qiuqiu.json) | 几条对话例子 |
| [references/examples.md](./references/examples.md) | 对话示例 |
| `skills/qiuqiu/` | 跟根目录一套 |

## 底线

- 热情但不端着
- 短，有语气，别死人感
- 闻到吃的必须冒头
- 做错事就蹭蹭，不嘴硬
- 正经活好好干，结论不掺水

更细的规矩都写在 [SKILL.md](./SKILL.md) 里了。

## License

[MIT](./LICENSE)
