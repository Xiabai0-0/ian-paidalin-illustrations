# 派大林 IP 图像资产生成提示词

> 本文档收录派大林 IP 全部待生成图像资产的完整提示词，可整段复制到任意生图产品（ChatGPT、Gemini、即梦、Midjourney 等）使用。角色块与 `paidalin-illustrations/references/paidalin-ip.md` 的“可复制角色块”同源；若角色设定后续调整，需同步更新本文档。

## 使用流程

1. 复制对应小节的完整提示词，粘贴到您的生图产品。若产品支持上传参考图，同时附上 `paidalin-illustrations/assets/ip-reference/paidalin-character-sheet.png` 并注明 "Match this character exactly, render in hand-drawn line art style instead of 3D"。
2. 按每节标注的建议尺寸生成；生成 1 张先验收，再批量生成其余。
3. 按标注文件名保存，放回对应路径，或发给助手归档并按 `references/qa-checklist.md` 验收。

| 资产 | 建议尺寸 | 保存路径 |
|---|---|---|
| 三视图 | 16:9（如 1792×1024） | `paidalin-illustrations/assets/ip-reference/paidalin-turnaround.png` |
| 面部特写 | 1:1（1024×1024） | `paidalin-illustrations/assets/ip-reference/paidalin-closeup.png` |
| 8 张校准图 | 16:9（如 1792×1024） | `examples/images/` 与 `paidalin-illustrations/assets/examples/` 各放一份同名副本 |

---

## A. 三视图 → 保存为 `paidalin-turnaround.png`

```text
Create one clean 16:9 character design sheet on a pure white background showing the same original wizard character PAIDALIN in exactly three full-body views: FRONT, SIDE, BACK, arranged left to right with generous white space between views.

Character design (must be identical across all three views): a pink five-point starfish body, rounded and plump, with a round head-top, two short stubby arms and two short stubby legs, no neck; big round eyes with highlights, soft curved thin eyebrows, gentle smile, blushing cheeks; a deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, a small copper goggle decoration on the brim, and a curled spiral hat tip; a deep-blue high-collar layered cape with silver vine embroidery and a fine gold chain with a blue teardrop gem pendant on the chest; a gold monocle on the right eye with a fine gold chain hanging to the collar; a crystal staff with a dark vine-wrapped wooden shaft and a blue crystal top held by a silver claw setting, held in one hand at the side or standing upright next to the body; one small coral-red heart floating beside the hat.

Relaxed neutral pose. Consistent height, body shape, outfit folds, staff, heart position, line weight, and color across all three views. Fine black hand-drawn line art with slightly wobbly pen lines and restrained flat color; pink body and deep-blue hat and cape as identity colors, gold chain and blue crystal as small accents. Lots of quiet white space.

No extra poses, no props beyond the staff, no environment, no shadow, no title, no text, no watermark, no costume change, no Patrick Star likeness, no flower shorts, no spread flat starfish arms, no human five fingers, no 3D render, no glossy texture.
```

## B. 面部特写 → 保存为 `paidalin-closeup.png`

```text
Create one clean close-up portrait of an original wizard character PAIDALIN on a pure white background, showing the head and upper torso, character facing slightly right.

Character design: a pink five-point starfish body with a round head, rounded and plump, no neck; big round eyes with white highlights, soft curved thin eyebrows, gentle closed smile, blushing cheeks; a deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery patterns, a small copper goggle decoration on the left brim, and a tall curled spiral hat tip bending backward; a gold monocle over the right eye with a fine gold chain hanging down to the high collar; deep-blue high-collar layered cape with silver vine embroidery, a small gold emblem clasp and a fine gold chain with a tiny blue teardrop gem pendant at the chest; one small coral-red heart floating in the empty space beside the hat.

Fine black hand-drawn line art with slightly wobbly pen lines and restrained flat color; pink body and deep-blue hat and cape as identity colors, gold chain and blue crystal as small accents. Lots of quiet white space around the character.

No environment, no shadow, no title, no text, no watermark, no extra characters, no Patrick Star likeness, no human five fingers, no 3D render, no glossy texture.
```

---

## C. 八张校准样图

以下 8 段提示词彼此独立，每段已包含完整角色块与规则，无需拼接。

### 01 → 保存为 `01-content-workbench.png`（Workflow / 内容工作台）

```text
Use case: calibration-illustration
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor: a messy-to-ready content workbench. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram. Pure white background, minimal black hand-drawn line art with slightly wobbly pen lines, lots of quiet white space.

Recurring IP character required:
派大林（PAIDALIN），固定个人 IP：粉色海星身体，圆钝五角轮廓（圆头顶、两侧短圆臂、底部短圆小腿），身体圆润无脖颈；圆大眼带高光，弧形细眉，温和微笑，脸颊腮红；头戴深蓝色宽檐弯角巫师帽，银线藤蔓刺绣，帽檐有铜色护目镜装饰，帽尖卷曲成螺旋；穿深蓝色高立领披肩与层叠银绣斗篷，胸口纹章扣配金链宝石挂饰；右眼单片金边眼镜，细金链垂至衣领；右手持水晶法杖（深色木柄缠藤蔓，顶端蓝色水晶，银色爪托）；身侧漂浮一颗珊瑚红小爱心。黑色细手绘线稿呈现，粉色身体与深蓝帽斗为主色，金色细链与蓝水晶为点缀，上色克制。默认不摘帽、不摘眼镜、不离法杖、不失爱心。气质安静、认真、克制，带轻微冷幽默。派大林必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
A messy-to-ready content workbench.

Structure type:
Workflow.

Core idea:
Raw messy material becomes one clean publishable page through deconstruct, cut, and recombine.

Composition and action:
派大林 stands at a low-tech paper workbench, tearing open crumpled source notes on the left, cutting and reordering paper strips, while the right side outputs one clean finished page. Left-to-right flow, but never draw it as a flowchart.

Suggested elements:
crumpled notes / paper strips / three-slot tray / finished page

Text (verbatim):
Use only these short handwritten labels and render them exactly, with no extra text:
"原始素材 RAW" / "拆解" / "重组" / "可发布 READY"

Color use:
CRITICAL: 派大林 himself is always fully colored — pink five-point starfish body, deep-blue hat and cape with silver embroidery, gold monocle and fine gold chain, blue crystal on the staff, and one floating coral-red heart. Only props, structures, and labels stay as black line art; never render the character himself as pure uncolored line art. Black for line art, structure, and main labels. Orange only for the main path or movement. Red only for a warning, correction, or result; the coral-red heart is part of the character and is not a semantic red. Blue only for evidence, feedback, or a secondary system state, and never repaints his hat or cape.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 派大林 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd; magic only makes the causal chain visible, never a fireworks show. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 派大林's identity anchors exactly. Same pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. No Patrick Star likeness, no flower shorts, no spread flat starfish limbs, no costume changes, no removing the hat, monocle, cape, staff, or heart. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D render, thick-paint texture, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, Patrick Star likeness, flower shorts, spread flat starfish arms, human five fingers, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei or Luming compositions, watermark.
```

### 02 → 保存为 `02-logic-repair.png`（系统局部 / 逻辑维修）｜v3：强化亲手修理动作

```text
Use case: calibration-illustration
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor: a logic machine missing one gear. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram. Pure white background, minimal black hand-drawn line art with slightly wobbly pen lines, lots of quiet white space.

Recurring IP character required:
派大林（PAIDALIN），固定个人 IP：粉色海星身体，圆钝五角轮廓（圆头顶、两侧短圆臂、底部短圆小腿），身体圆润无脖颈；圆大眼带高光，弧形细眉，温和微笑，脸颊腮红；头戴深蓝色宽檐弯角巫师帽，银线藤蔓刺绣，帽檐有铜色护目镜装饰，帽尖卷曲成螺旋；穿深蓝色高立领披肩与层叠银绣斗篷，胸口纹章扣配金链宝石挂饰；右眼单片金边眼镜，细金链垂至衣领；右手持水晶法杖（深色木柄缠藤蔓，顶端蓝色水晶，银色爪托）；身侧漂浮一颗珊瑚红小爱心。黑色细手绘线稿呈现，粉色身体与深蓝帽斗为主色，金色细链与蓝水晶为点缀，上色克制。默认不摘帽、不摘眼镜、不离法杖、不失爱心。气质安静、认真、克制，带轻微冷幽默。派大林必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
A logic machine missing one gear.

Structure type:
System close-up.

Core idea:
Broken logic is verified with evidence and repaired at the exact breakpoint.

Composition and action:
A partially visible "opinion machine" occupies the right side of the canvas with one gear fallen off. 派大林 half-crouches in front of it, holding a magnifying glass close to the broken spot in one hand to verify, and using his staff like a screwdriver to re-attach the fallen gear with the other hand. One evidence card leans against the machine. He is actively repairing the machine at the exact breakpoint, not posing beside it; remove the broken-gear board lying on the ground.

Suggested elements:
partial machine / fallen gear / magnifying glass / evidence card

Text (verbatim):
Use only these short handwritten labels and render them exactly, with no extra text:
"断点 BUG" / "证据" / "修复 FIX" / "逻辑"

Color use:
CRITICAL: 派大林 himself is always fully colored — pink five-point starfish body, deep-blue hat and cape with silver embroidery, gold monocle and fine gold chain, blue crystal on the staff, and one floating coral-red heart. Only props, structures, and labels stay as black line art; never render the character himself as pure uncolored line art. Black for line art, structure, and main labels. Orange only for the main path or movement. Red only for a warning, correction, or result; the coral-red heart is part of the character and is not a semantic red. Blue only for evidence, feedback, or a secondary system state, and never repaints his hat or cape.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 派大林 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd; magic only makes the causal chain visible, never a fireworks show. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 派大林's identity anchors exactly. Same pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. No Patrick Star likeness, no flower shorts, no spread flat starfish limbs, no costume changes, no removing the hat, monocle, cape, staff, or heart. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D render, thick-paint texture, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, Patrick Star likeness, flower shorts, spread flat starfish arms, human five fingers, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei or Luming compositions, watermark.
```

### 03 → 保存为 `03-draft-before-after.png`（前后对比 / 草稿前后）｜v2：禁用漏斗构图

```text
Use case: calibration-illustration
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor: before and after of a draft. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram. Pure white background, minimal black hand-drawn line art with slightly wobbly pen lines, lots of quiet white space.

Recurring IP character required:
派大林（PAIDALIN），固定个人 IP：粉色海星身体，圆钝五角轮廓（圆头顶、两侧短圆臂、底部短圆小腿），身体圆润无脖颈；圆大眼带高光，弧形细眉，温和微笑，脸颊腮红；头戴深蓝色宽檐弯角巫师帽，银线藤蔓刺绣，帽檐有铜色护目镜装饰，帽尖卷曲成螺旋；穿深蓝色高立领披肩与层叠银绣斗篷，胸口纹章扣配金链宝石挂饰；右眼单片金边眼镜，细金链垂至衣领；右手持水晶法杖（深色木柄缠藤蔓，顶端蓝色水晶，银色爪托）；身侧漂浮一颗珊瑚红小爱心。黑色细手绘线稿呈现，粉色身体与深蓝帽斗为主色，金色细链与蓝水晶为点缀，上色克制。默认不摘帽、不摘眼镜、不离法杖、不失爱心。气质安静、认真、克制，带轻微冷幽默。派大林必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
Before and after of a draft.

Structure type:
Before / after comparison.

Core idea:
Deleting filler words keeps only the one key sentence.

Composition and action:
Left desk piled with messy drafts and repeated sentences; right side keeps only one clear page. 派大林 stands between them, physically crossing out filler words with a red pen and moving the single key-sentence page to the right with his own hands. Strictly no funnel of any kind — the old funnel composition is forbidden; the trash bin stays plain with no face.

Suggested elements:
messy draft pile / red pen / one clean page

Text (verbatim):
Use only these short handwritten labels and render them exactly, with no extra text:
"乱 DRAFT" / "删" / "重点 KEY" / "清晰 CLEAR"

Color use:
CRITICAL: 派大林 himself is always fully colored — pink five-point starfish body, deep-blue hat and cape with silver embroidery, gold monocle and fine gold chain, blue crystal on the staff, and one floating coral-red heart. Only props, structures, and labels stay as black line art; never render the character himself as pure uncolored line art. Black for line art, structure, and main labels. Orange only for the main path or movement. Red only for a warning, correction, or result; the coral-red heart is part of the character and is not a semantic red. Blue only for evidence, feedback, or a secondary system state, and never repaints his hat or cape.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 派大林 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd; magic only makes the causal chain visible, never a fireworks show. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 派大林's identity anchors exactly. Same pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. No Patrick Star likeness, no flower shorts, no spread flat starfish limbs, no costume changes, no removing the hat, monocle, cape, staff, or heart. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D render, thick-paint texture, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, Patrick Star likeness, flower shorts, spread flat starfish arms, human five fingers, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei or Luming compositions, watermark.
```

### 04 → 保存为 `04-stuck-to-insight.png`（角色状态 / 卡住到想通）｜v2：修复角色上色

```text
Use case: calibration-illustration
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor: from stuck to insight. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram. Pure white background, minimal black hand-drawn line art with slightly wobbly pen lines, lots of quiet white space.

Recurring IP character required:
派大林（PAIDALIN），固定个人 IP：粉色海星身体，圆钝五角轮廓（圆头顶、两侧短圆臂、底部短圆小腿），身体圆润无脖颈；圆大眼带高光，弧形细眉，温和微笑，脸颊腮红；头戴深蓝色宽檐弯角巫师帽，银线藤蔓刺绣，帽檐有铜色护目镜装饰，帽尖卷曲成螺旋；穿深蓝色高立领披肩与层叠银绣斗篷，胸口纹章扣配金链宝石挂饰；右眼单片金边眼镜，细金链垂至衣领；右手持水晶法杖（深色木柄缠藤蔓，顶端蓝色水晶，银色爪托）；身侧漂浮一颗珊瑚红小爱心。黑色细手绘线稿呈现，粉色身体与深蓝帽斗为主色，金色细链与蓝水晶为点缀，上色克制。默认不摘帽、不摘眼镜、不离法杖、不失爱心。气质安静、认真、克制，带轻微冷幽默。派大林必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
From stuck to insight.

Structure type:
Character state sequence.

Core idea:
A four-step state change: stuck, observe, redraw, finally get it.

Composition and action:
Four loose sequential poses of the same 派大林: stuck facing a note cloud, quietly observing, redrawing on a storyboard board, then nodding slightly as a second tiny heart appears. Do not draw comic grid frames.

Suggested elements:
note cloud / storyboard / small stool / confirmation gesture

Text (verbatim):
Use only these short handwritten labels and render them exactly, with no extra text:
"卡住 STUCK" / "观察" / "重画" / "想通 AHA"

Color use:
CRITICAL: 派大林 himself is always fully colored — pink five-point starfish body, deep-blue hat and cape with silver embroidery, gold monocle and fine gold chain, blue crystal on the staff, and one floating coral-red heart. Only props, structures, and labels stay as black line art; never render the character himself as pure uncolored line art. Black for line art, structure, and main labels. Orange only for the main path or movement. Red only for a warning, correction, or result; the coral-red heart is part of the character and is not a semantic red. Blue only for evidence, feedback, or a secondary system state, and never repaints his hat or cape.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 派大林 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd; magic only makes the causal chain visible, never a fireworks show. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 派大林's identity anchors exactly. Same pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. No Patrick Star likeness, no flower shorts, no spread flat starfish limbs, no costume changes, no removing the hat, monocle, cape, staff, or heart. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D render, thick-paint texture, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, Patrick Star likeness, flower shorts, spread flat starfish arms, human five fingers, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei or Luming compositions, watermark.
```

### 05 → 保存为 `05-evidence-support.png`（概念隐喻 / 证据承重）｜v2：修复上色与动作

```text
Use case: calibration-illustration
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor: evidence holding up a claim. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram. Pure white background, minimal black hand-drawn line art with slightly wobbly pen lines, lots of quiet white space.

Recurring IP character required:
派大林（PAIDALIN），固定个人 IP：粉色海星身体，圆钝五角轮廓（圆头顶、两侧短圆臂、底部短圆小腿），身体圆润无脖颈；圆大眼带高光，弧形细眉，温和微笑，脸颊腮红；头戴深蓝色宽檐弯角巫师帽，银线藤蔓刺绣，帽檐有铜色护目镜装饰，帽尖卷曲成螺旋；穿深蓝色高立领披肩与层叠银绣斗篷，胸口纹章扣配金链宝石挂饰；右眼单片金边眼镜，细金链垂至衣领；右手持水晶法杖（深色木柄缠藤蔓，顶端蓝色水晶，银色爪托）；身侧漂浮一颗珊瑚红小爱心。黑色细手绘线稿呈现，粉色身体与深蓝帽斗为主色，金色细链与蓝水晶为点缀，上色克制。默认不摘帽、不摘眼镜、不离法杖、不失爱心。气质安静、认真、克制，带轻微冷幽默。派大林必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
Evidence holding up a claim.

Structure type:
Concept metaphor.

Core idea:
A claim stays stable only when evidence boards are wedged underneath.

Composition and action:
A small claim-labeled platform wobbles. 派大林 bends down and pushes solid evidence boards under it with both hands, one by one; the platform turns from tilted to stable exactly where he pushes. He causes the stabilizing; he does not just hold a sign. Absurd but physically coherent.

Suggested elements:
wobbly platform / evidence boards / small mallet

Text (verbatim):
Use only these short handwritten labels and render them exactly, with no extra text:
"观点 CLAIM" / "证据 EVIDENCE" / "承重" / "可信 TRUST"

Color use:
CRITICAL: 派大林 himself is always fully colored — pink five-point starfish body, deep-blue hat and cape with silver embroidery, gold monocle and fine gold chain, blue crystal on the staff, and one floating coral-red heart. Only props, structures, and labels stay as black line art; never render the character himself as pure uncolored line art. Black for line art, structure, and main labels. Orange only for the main path or movement. Red only for a warning, correction, or result; the coral-red heart is part of the character and is not a semantic red. Blue only for evidence, feedback, or a secondary system state, and never repaints his hat or cape.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 派大林 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd; magic only makes the causal chain visible, never a fireworks show. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 派大林's identity anchors exactly. Same pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. No Patrick Star likeness, no flower shorts, no spread flat starfish limbs, no costume changes, no removing the hat, monocle, cape, staff, or heart. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D render, thick-paint texture, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, Patrick Star likeness, flower shorts, spread flat starfish arms, human five fingers, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei or Luming compositions, watermark.
```

### 06 → 保存为 `06-method-stack.png`（方法分层 / 方法搭层）｜v2：修复上色与标签

```text
Use case: calibration-illustration
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor: building a method layer by layer. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram. Pure white background, minimal black hand-drawn line art with slightly wobbly pen lines, lots of quiet white space.

Recurring IP character required:
派大林（PAIDALIN），固定个人 IP：粉色海星身体，圆钝五角轮廓（圆头顶、两侧短圆臂、底部短圆小腿），身体圆润无脖颈；圆大眼带高光，弧形细眉，温和微笑，脸颊腮红；头戴深蓝色宽檐弯角巫师帽，银线藤蔓刺绣，帽檐有铜色护目镜装饰，帽尖卷曲成螺旋；穿深蓝色高立领披肩与层叠银绣斗篷，胸口纹章扣配金链宝石挂饰；右眼单片金边眼镜，细金链垂至衣领；右手持水晶法杖（深色木柄缠藤蔓，顶端蓝色水晶，银色爪托）；身侧漂浮一颗珊瑚红小爱心。黑色细手绘线稿呈现，粉色身体与深蓝帽斗为主色，金色细链与蓝水晶为点缀，上色克制。默认不摘帽、不摘眼镜、不离法杖、不失爱心。气质安静、认真、克制，带轻微冷幽默。派大林必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
Building a method layer by layer.

Structure type:
Layered method.

Core idea:
Facts are the base, insight the middle, expression the top, with a publish card at the very top.

Composition and action:
派大林 builds an irregular floating paper-brick tower of exactly four layers beside him, stacking from the bottom: 事实 FACT as base, 洞察 INSIGHT as middle, 表达 STORY as upper layer, and the 发布 GO card on top. He places each brick with his own hands and steadies the tower. Never a formal pyramid; exactly four layers.

Suggested elements:
floating paper bricks / wooden frame / publish card

Text (verbatim):
Use only these short handwritten labels and render them exactly, with no extra text:
"事实 FACT" / "洞察 INSIGHT" / "表达 STORY" / "发布 GO"

Color use:
CRITICAL: 派大林 himself is always fully colored — pink five-point starfish body, deep-blue hat and cape with silver embroidery, gold monocle and fine gold chain, blue crystal on the staff, and one floating coral-red heart. Only props, structures, and labels stay as black line art; never render the character himself as pure uncolored line art. Black for line art, structure, and main labels. Orange only for the main path or movement. Red only for a warning, correction, or result; the coral-red heart is part of the character and is not a semantic red. Blue only for evidence, feedback, or a secondary system state, and never repaints his hat or cape.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 派大林 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd; magic only makes the causal chain visible, never a fireworks show. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 派大林's identity anchors exactly. Same pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. No Patrick Star likeness, no flower shorts, no spread flat starfish limbs, no costume changes, no removing the hat, monocle, cape, staff, or heart. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D render, thick-paint texture, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, Patrick Star likeness, flower shorts, spread flat starfish arms, human five fingers, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei or Luming compositions, watermark.
```

### 07 → 保存为 `07-topic-to-publish.png`（地图路线 / 选题到发布）｜v2：补爱心与完整标签

```text
Use case: calibration-illustration
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor: topic to publish route. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram. Pure white background, minimal black hand-drawn line art with slightly wobbly pen lines, lots of quiet white space.

Recurring IP character required:
派大林（PAIDALIN），固定个人 IP：粉色海星身体，圆钝五角轮廓（圆头顶、两侧短圆臂、底部短圆小腿），身体圆润无脖颈；圆大眼带高光，弧形细眉，温和微笑，脸颊腮红；头戴深蓝色宽檐弯角巫师帽，银线藤蔓刺绣，帽檐有铜色护目镜装饰，帽尖卷曲成螺旋；穿深蓝色高立领披肩与层叠银绣斗篷，胸口纹章扣配金链宝石挂饰；右眼单片金边眼镜，细金链垂至衣领；右手持水晶法杖（深色木柄缠藤蔓，顶端蓝色水晶，银色爪托）；身侧漂浮一颗珊瑚红小爱心。黑色细手绘线稿呈现，粉色身体与深蓝帽斗为主色，金色细链与蓝水晶为点缀，上色克制。默认不摘帽、不摘眼镜、不离法杖、不失爱心。气质安静、认真、克制，带轻微冷幽默。派大林必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
Topic to publish route.

Structure type:
Map route.

Core idea:
Publishing requires checking every node and correcting wrong turns along the way.

Composition and action:
A bent route made of tape passes four checkpoints. 派大林 walks along it, verifying nodes with a red pen, and turns one wrong direction sign back to the correct direction. His coral-red heart floats clearly beside his hat, always visible. All four labels must render completely, especially 打磨 EDIT in full, never truncated.

Suggested elements:
tape route / four checkpoints / direction sign / red pen

Text (verbatim):
Use only these short handwritten labels and render them exactly, with no extra text:
"选题 TOPIC" / "验证 CHECK" / "打磨 EDIT" / "发布 LIVE"

Color use:
CRITICAL: 派大林 himself is always fully colored — pink five-point starfish body, deep-blue hat and cape with silver embroidery, gold monocle and fine gold chain, blue crystal on the staff, and one floating coral-red heart. Only props, structures, and labels stay as black line art; never render the character himself as pure uncolored line art. Black for line art, structure, and main labels. Orange only for the main path or movement. Red only for a warning, correction, or result; the coral-red heart is part of the character and is not a semantic red. Blue only for evidence, feedback, or a secondary system state, and never repaints his hat or cape.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 派大林 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd; magic only makes the causal chain visible, never a fireworks show. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 派大林's identity anchors exactly. Same pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. No Patrick Star likeness, no flower shorts, no spread flat starfish limbs, no costume changes, no removing the hat, monocle, cape, staff, or heart. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D render, thick-paint texture, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, Patrick Star likeness, flower shorts, spread flat starfish arms, human five fingers, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei or Luming compositions, watermark.
```

### 08 → 保存为 `08-revise-mini-comic.png`（小漫画分镜 / 修改完成）

```text
Use case: calibration-illustration
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor: a revise-and-done mini comic. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram. Pure white background, minimal black hand-drawn line art with slightly wobbly pen lines, lots of quiet white space.

Recurring IP character required:
派大林（PAIDALIN），固定个人 IP：粉色海星身体，圆钝五角轮廓（圆头顶、两侧短圆臂、底部短圆小腿），身体圆润无脖颈；圆大眼带高光，弧形细眉，温和微笑，脸颊腮红；头戴深蓝色宽檐弯角巫师帽，银线藤蔓刺绣，帽檐有铜色护目镜装饰，帽尖卷曲成螺旋；穿深蓝色高立领披肩与层叠银绣斗篷，胸口纹章扣配金链宝石挂饰；右眼单片金边眼镜，细金链垂至衣领；右手持水晶法杖（深色木柄缠藤蔓，顶端蓝色水晶，银色爪托）；身侧漂浮一颗珊瑚红小爱心。黑色细手绘线稿呈现，粉色身体与深蓝帽斗为主色，金色细链与蓝水晶为点缀，上色克制。默认不摘帽、不摘眼镜、不离法杖、不失爱心。气质安静、认真、克制，带轻微冷幽默。派大林必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
Revise-and-done mini comic.

Structure type:
Mini comic panels.

Core idea:
An off-topic draft is restructured and finally stands firm.

Composition and action:
Three open comic panels: panel 1 派大林 hands in an off-topic draft; panel 2 he re-cuts and re-pastes the structure; panel 3 the finished page stands firm and he makes a small quiet confirmation gesture. Panel borders incomplete, generous white space.

Suggested elements:
draft page / scissors and tape / finished page

Text (verbatim):
Use only these short handwritten labels and render them exactly, with no extra text:
"初稿 V1" / "偏了" / "修改 REVISE" / "完成 DONE"

Color use:
CRITICAL: 派大林 himself is always fully colored — pink five-point starfish body, deep-blue hat and cape with silver embroidery, gold monocle and fine gold chain, blue crystal on the staff, and one floating coral-red heart. Only props, structures, and labels stay as black line art; never render the character himself as pure uncolored line art. Black for line art, structure, and main labels. Orange only for the main path or movement. Red only for a warning, correction, or result; the coral-red heart is part of the character and is not a semantic red. Blue only for evidence, feedback, or a secondary system state, and never repaints his hat or cape.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 派大林 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd; magic only makes the causal chain visible, never a fireworks show. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 派大林's identity anchors exactly. Same pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. No Patrick Star likeness, no flower shorts, no spread flat starfish limbs, no costume changes, no removing the hat, monocle, cape, staff, or heart. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D render, thick-paint texture, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, Patrick Star likeness, flower shorts, spread flat starfish arms, human five fingers, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei or Luming compositions, watermark.
```

---

## 验收提示

生成后把图片放入上表路径（或发给助手归档）。助手将按 `paidalin-illustrations/references/qa-checklist.md` 验收，重点核验：

- 三视图：三个视角同一角色、单片眼镜在右眼、螺旋帽尖可见、法杖在场（B 节）
- 校准图：派大林锚点齐全、标签逐字正确、无人类五指、不像派大星、不是 3D 渲染（A 节）
- 不合格的图片会收到对应的重生成提示词（身份漂移 / 动作太装饰 / 标签错误三类迭代模板见 `references/prompt-template.md`）
