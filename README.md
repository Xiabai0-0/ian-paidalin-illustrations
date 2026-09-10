# 派大林个人 IP 怪诞正文配图 Skill

> 把中文文章里的判断、流程、状态和隐喻，变成角色统一、白底留白、怪诞但清楚的 16:9 手绘配图。

本项目是 [helloianneo/ian-xiaohei-illustrations](https://github.com/helloianneo/ian-xiaohei-illustrations) 的个人 IP 改造版本，保留原项目的视觉 DNA、构图引擎和 MIT 许可，并把默认角色替换为“派大林”。

## 这不是改名字

稳定个人 IP 的核心是一条可复用规则链：

```text
外形锚点 → 性格锚点 → 职业动作 → 场景映射 → 禁忌 → 三视图 → 八图校准 → QA
```

派大林的固定锚点是：粉色海星身体（圆钝五角轮廓、短圆小腿）、深蓝银绣弯角巫师帽（帽檐护目镜装饰、螺旋帽尖）、高立领披肩与层叠银绣斗篷、右眼单片金边眼镜、右手水晶法杖、身侧漂浮珊瑚红小爱心。角色定位是安静、认真、略带冷幽默的“认知魔法师”；核心动作沿用内容拆解者语法——拆案例、写文案、画分镜、贴证据、修结构、校验输出——并可用魔法装置让动作因果可见。

## 最小改造面

迁移到另一个个人 IP 时，核心只需调整四个文件：

1. `paidalin-illustrations/SKILL.md`：功能定位、触发语义与工作流。
2. `paidalin-illustrations/references/paidalin-ip.md`：角色外形、性格、动作、场景映射和禁忌。
3. `paidalin-illustrations/references/prompt-template.md`：把角色规则注入每张图。
4. `paidalin-illustrations/references/qa-checklist.md`：把“像不像同一个 IP”变成可检查门槛。

不要默认改 `style-dna.md` 和 `composition-patterns.md`。前者是风格引擎，后者是构图引擎，应该与具体人物解耦。

## 角色形象

![派大林形象源头](paidalin-illustrations/assets/ip-reference/paidalin-character-sheet.png)

形象源头参考保存在 `paidalin-illustrations/assets/ip-reference/`，用于生成时直接锁定身份。三视图 `paidalin-turnaround.png` 与面部特写 `paidalin-closeup.png` 就位后，作为场景图的直接角色参考。

## 八张校准样图

| 场景 | 构图类型 | 核心动作 |
|---|---|---|
| 内容工作台 | Workflow | 拆开、剪短、重组素材 |
| 逻辑维修 | 系统局部 | 查证并修复断裂逻辑 |
| 草稿前后 | 前后对比 | 删除赘词、保留重点 |
| 卡住到想通 | 角色状态 | 观察、重画、想通 |
| 证据承重 | 概念隐喻 | 用证据支撑观点 |
| 方法搭层 | 方法分层 | 从事实向上搭建表达 |
| 选题到发布 | 地图路线 | 校验节点、修正方向 |
| 修改完成 | 小漫画分镜 | 初稿、修改、完成 |

| | |
|---|---|
| ![内容工作台](examples/images/01-content-workbench.png) | ![逻辑维修](examples/images/02-logic-repair.png) |
| ![草稿前后](examples/images/03-draft-before-after.png) | ![卡住到想通](examples/images/04-stuck-to-insight.png) |
| ![证据承重](examples/images/05-evidence-support.png) | ![方法搭层](examples/images/06-method-stack.png) |
| ![选题到发布](examples/images/07-topic-to-publish.png) | ![修改完成](examples/images/08-revise-mini-comic.png) |

这些图片只用于校准角色身份、留白、线条密度、动作语法与标签克制程度。生成新图时必须根据当前文章重新发明物理隐喻，禁止照抄样图构图。可复现校准任务见 `examples/prompts.md`，外部生图完整提示词见 `examples/image-prompts.md`。

## 安装

```bash
git clone https://github.com/YOUR-GITHUB/paidalin-illustrations.git
mkdir -p "${CODEX_HOME:-$HOME/.codex}/skills"
cp -R ./paidalin-illustrations/paidalin-illustrations "${CODEX_HOME:-$HOME/.codex}/skills/"
```

安装后，在 Codex 中使用：

```text
Use $paidalin-illustrations 为这篇中文文章设计并生成 5 张派大林个人 IP 风格正文配图。
```

## 目录结构

```text
.
├── LICENSE
├── NOTICE.md
├── README.md
├── examples/
│   ├── images/                 # 8 张派大林校准样图
│   ├── prompts.md              # 8 个可复现校准任务
│   └── image-prompts.md        # 可直接复制的外部生图完整提示词
└── paidalin-illustrations/
    ├── SKILL.md
    ├── agents/openai.yaml
    ├── assets/
    │   ├── ip-reference/       # 形象源头 + 三视图 + 特写
    │   └── examples/           # Skill 运行时低频校准样图
    └── references/
        ├── style-dna.md
        ├── paidalin-ip.md
        ├── composition-patterns.md
        ├── prompt-template.md
        └── qa-checklist.md
```

## 许可与署名

代码与 Skill 结构沿用 MIT License。原始项目、视觉方法与“小黑”体系由 [Ian](https://github.com/helloianneo) 创建；本仓库保留上游署名，派大林角色规则与校准资产为本次衍生改造。
