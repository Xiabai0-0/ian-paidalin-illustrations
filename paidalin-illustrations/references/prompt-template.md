# 派大林正文配图生图模板

每张图单独生成。先从 `paidalin-ip.md` 复制“可复制角色块”，再填入内容变量。可用时，把 `assets/ip-reference/paidalin-turnaround.png` 作为直接角色参考；三视图尚未生成前，退回 `assets/ip-reference/paidalin-character-sheet.png` 作为形象源头参考。参考图的渲染质感只用于锁定形象，最终交付仍是白底黑线手绘风格。

```text
Use case: illustration-story
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor from the article. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram.

Input images:
Image 1: direct identity reference for 派大林 (PAIDALIN). Preserve the same pink starfish body shape, wizard hat, cape, monocle, staff, floating heart, and all fixed outfit details.

Scene/backdrop:
Pure white background. Minimal black hand-drawn line art with slightly wobbly pen lines. Lots of quiet white space. No room background, paper texture, gradient, shadow, UI, or decorative frame.

Recurring IP character required:
派大林（PAIDALIN），固定个人 IP：粉色海星身体，圆钝五角轮廓（圆头顶、两侧短圆臂、底部短圆小腿），身体圆润无脖颈；圆大眼带高光，弧形细眉，温和微笑，脸颊腮红；头戴深蓝色宽檐弯角巫师帽，银线藤蔓刺绣，帽檐有铜色护目镜装饰，帽尖卷曲成螺旋；穿深蓝色高立领披肩与层叠银绣斗篷，胸口纹章扣配金链宝石挂饰；右眼单片金边眼镜，细金链垂至衣领；右手持水晶法杖（深色木柄缠藤蔓，顶端蓝色水晶，银色爪托）；身侧漂浮一颗珊瑚红小爱心。黑色细手绘线稿呈现，粉色身体与深蓝帽斗为主色，金色细链与蓝水晶为点缀，上色克制。默认不摘帽、不摘眼镜、不离法杖、不失爱心。气质安静、认真、克制，带轻微冷幽默。派大林必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
{正文配图主题}

Structure type:
{Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{一句话说明这张图要表达的判断或变化}

Composition and action:
{派大林在哪里；他正在拆、写、画、贴、圈、剪、校验、排序、搭建、复盘或修补什么；魔法装置或法杖如何让动作因果可见；物件如何响应他的动作；信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {可选元素4}

Text (verbatim):
Use only these 2-6 short handwritten labels and render them exactly, with no extra text:
"{中文标签1}" / "{ENGLISH 1}" / "{中文标签2}" / "{ENGLISH 2}" / "{可选标签3}"

Color use:
Black for line art, structure, and main labels. Pink starfish body and deep-blue hat and cape only on 派大林 as fixed identity colors; gold chain and blue crystal as small accents on him. Orange only for the main path or movement. Red only for a warning, correction, or result; the coral-red heart is part of the character and is not a semantic red. Blue only for evidence, feedback, or a secondary system state, and never repaints his hat or cape.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 派大林 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd; magic only makes the causal chain visible, never a fireworks show. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 派大林's identity anchors exactly. Same pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. No Patrick Star likeness, no flower shorts, no spread flat starfish limbs, no costume changes, no removing the hat, monocle, cape, staff, or heart. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D render, thick-paint texture, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, Patrick Star likeness, flower shorts, spread flat starfish arms, human five fingers, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei or Luming compositions, watermark.
```

## 三视图模板

```text
Use case: identity-preserve
Asset type: character turnaround sheet
Create one clean 16:9 character design sheet on a pure white background showing the same 派大林 in exactly three full-body views: FRONT, SIDE, BACK. Preserve the supplied character's pink five-point starfish body with short stubby arms and legs, deep-blue wide-brimmed bent-corner wizard hat with silver vine embroidery, goggle decoration, and curled spiral tip, deep-blue high-collar layered silver-embroidered cape, gold monocle on the right eye with a fine chain, vine-wrapped crystal staff, and one floating coral-red heart. Relaxed neutral pose. Consistent height, body shape, outfit folds, staff, heart position, line weight, and color across all three views. Fine black hand-drawn line art with restrained flat color. No extra poses, no props beyond the staff, no environment, no shadow, no title, no watermark, no costume change, no Patrick Star likeness, no human five fingers.
```

## 迭代模板

### 身份漂移

```text
Regenerate the same scene and concept. Change only the character identity: match the supplied 派大林 reference exactly, including the pink five-point starfish body, deep-blue wizard hat with silver embroidery and curled spiral tip, high-collar layered silver-embroidered cape, gold monocle on the right eye, vine-wrapped crystal staff, and one floating coral-red heart. Keep composition, action, labels, white background, and line style unchanged.
```

### 动作太装饰

```text
Regenerate with the same core idea and sparse white layout. Make 派大林 physically cause the central transformation through one clear content-creator action. Remove any flowchart-like pointing pose and any pure magic fireworks. Keep his identity, labels, props, and color rules unchanged.
```

### 标签错误

```text
Regenerate the image with the same character, scene, composition, and style. Use only these exact short labels: "{标签列表}". Do not add, translate, merge, or rewrite any text.
```
