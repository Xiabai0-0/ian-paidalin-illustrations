# 鹿小鸣正文配图生图模板

每张图单独生成。先从 `xiaohei-ip.md` 复制“可复制角色块”，再填入内容变量。可用时，把 `assets/ip-reference/luming-turnaround.png` 作为直接角色参考。

```text
Use case: illustration-story
Asset type: 16:9 horizontal Chinese article illustration

Primary request:
Create one standalone illustration that visualizes exactly one cognitive anchor from the article. The scene should feel like a strange but plausible hand-drawn content workshop, not a slide or formal diagram.

Input images:
Image 1: direct identity reference for 鹿小鸣 (LUMING). Preserve the same face, hair, outfit, body proportions, and black-white-red sneakers.

Scene/backdrop:
Pure white background. Minimal black hand-drawn line art with slightly wobbly pen lines. Lots of quiet white space. No room background, paper texture, gradient, shadow, UI, or decorative frame.

Recurring IP character required:
鹿小鸣（LUMING），固定个人 IP：年轻东亚男性，深棕色蓬松短发，顶部自然翘起发束，碎刘海，清澈的深棕大眼，温和粗眉，圆润偏椭圆脸；偏瘦、约 5.5-6.5 头身；穿无图案的黑色宽松短袖 T 恤、黑色宽松长裤、黑白红低帮球鞋。黑色细手绘线稿，少量暖肤色与深棕发色，红色仅作球鞋小面积识别色。默认无眼镜、无帽子、无首饰。气质安静、认真、克制，带轻微冷幽默。鹿小鸣必须亲手执行画面中的核心认知动作，不能作为角落装饰。

Theme:
{正文配图主题}

Structure type:
{Workflow / 系统局部 / 前后对比 / 角色状态 / 概念隐喻 / 方法分层 / 地图路线 / 小漫画分镜}

Core idea:
{一句话说明这张图要表达的判断或变化}

Composition and action:
{鹿小鸣在哪里；他正在拆、写、画、贴、圈、剪、校验、排序、搭建、复盘或修补什么；物件如何响应他的动作；信息如何流动}

Suggested elements:
{元素1} / {元素2} / {元素3} / {可选元素4}

Text (verbatim):
Use only these 2-6 short handwritten labels and render them exactly, with no extra text:
"{中文标签1}" / "{ENGLISH 1}" / "{中文标签2}" / "{ENGLISH 2}" / "{可选标签3}"

Color use:
Black for line art, outfit, structure, and main labels. Warm skin and dark-brown hair only on 鹿小鸣. Orange only for the main path or movement. Red only for a warning, correction, result, or sneaker accents. Blue only for evidence, feedback, or a secondary system state.

Composition constraints:
Keep the main subject around 40%-60% of the canvas and at least 35% pure white space. One image explains only one structure. 鹿小鸣 must be large enough to verify identity and must cause the visual change. Make props low-tech, tactile, and slightly absurd. Use an asymmetrical editorial composition unless the selected structure requires a split or sequence.

Invariants:
Preserve 鹿小鸣's identity anchors exactly. Same dark-brown tousled hair, brown eyes, black oversized T-shirt, loose black trousers, and black-white-red low-top sneakers. No glasses, no denim, no costume changes. Keep his personality serious, calm, and subtly humorous.

Avoid:
PPT infographic, formal flowchart, commercial vector illustration, dense explainer, realistic office background, app UI, glossy 3D, manga action poster, children's cartoon, 2-3-head chibi, cute mascot, title in the top-left, structure-name text, long sentences, garbled labels, extra fingers, duplicate limbs, copied Xiaohei compositions, watermark.
```

## 三视图模板

```text
Use case: identity-preserve
Asset type: character turnaround sheet
Create one clean 16:9 character design sheet on a pure white background showing the same 鹿小鸣 in exactly three full-body views: FRONT, SIDE, BACK. Preserve the supplied character's face, dark-brown tousled short hair, brown eyes, black oversized T-shirt, loose black trousers, and black-white-red low-top sneakers. Young East Asian male, slim, 6-head proportion, relaxed neutral pose, arms naturally at sides. Consistent height, anatomy, outfit folds, footwear, line weight, and color across all three views. Fine black hand-drawn line art with restrained flat color. No extra poses, no props, no environment, no shadow, no title, no watermark, no costume change, no glasses.
```

## 迭代模板

### 身份漂移

```text
Regenerate the same scene and concept. Change only the character identity: match the supplied 鹿小鸣 reference exactly, including dark-brown tousled hair, brown eyes, black oversized T-shirt, loose black trousers, and black-white-red sneakers. Keep composition, action, labels, white background, and line style unchanged.
```

### 动作太装饰

```text
Regenerate with the same core idea and sparse white layout. Make 鹿小鸣 physically cause the central transformation through one clear content-creator action. Remove any flowchart-like pointing pose. Keep his identity, labels, props, and color rules unchanged.
```

### 标签错误

```text
Regenerate the image with the same character, scene, composition, and style. Use only these exact short labels: "{标签列表}". Do not add, translate, merge, or rewrite any text.
```
