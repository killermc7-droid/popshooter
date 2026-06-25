# 微缩 + 休闲英雄射击 —— Fab 商城资产匹配清单

> 依据参考图（角色 `_front_char.png` / 场景两张 STYLARTS 截图）在 Fab 商城逐项匹配。
> 整体技术栈 = 玩法框架 + 场景资产 + 角色资产 + 武器道具。

---

## 0. 玩法框架（用户提供链接）

| 资产 | 作用 | 链接 |
|---|---|---|
| **Narrative Pro 2 - Complete Game Framework** | UE5 完整玩法框架：战斗(GAS)、武器(火器/近战)、NPC、同伴跟随、背包、任务、存档、开放世界 —— 作为「英雄射击」核心底层 | https://www.fab.com/listings/954b0610-9c29-4dd6-9900-d3c855b26741 |

---

## 1. 场景资产 —— ✅ 精准命中（即你的场景参考图本体）

| 资产 | 匹配说明 | 链接 |
|---|---|---|
| **Stylized Christmas Amusement Park** (StylArts / Leartes) | 场景图右下 "STYLARTS" 水印来源。含摩天轮、旋转木马、马戏帐篷、飞镖摊、圣诞树等 80 资产；Stylized / Low Poly / Game Ready / AAA；UE5 + ULAT 关卡工具 | https://www.fab.com/listings/a5c7ab8b-8bf6-40ce-8e0d-ba69999dee93 |

**演示视频**：https://www.youtube.com/watch?v=61Zi84jghfE

### 同作者「同品质」扩展场景（微缩主题，风格统一）
| 资产 | 用途 | 链接 |
|---|---|---|
| Minipoly Series - Modern Island City | 微缩城市，贴合「微缩」主题 | https://www.fab.com/listings/3af76404-4e65-4201-ba10-76de4ce500d8 |
| Minipoly Series - Race Track | 微缩赛道关卡变体 | https://www.fab.com/listings/310dc380-d595-4250-adc0-d6da48d2283c |
| Minipoly Series - Mythic Castle | 微缩城堡 | https://www.fab.com/listings/5ded1474-0337-40cd-a6b1-40c3ab7aa16c |
| Stylized Medieval Market Fatpack | 风格化市集摊位道具 | https://www.fab.com/listings/ef269476-b561-4000-a418-694d97905abe |

---

## 2. 角色资产 —— ⚠️ 商城无完全相同件（原创概念角色）

经多组特征关键词（兔耳针织帽 / 双麻花辫 / 红条纹背带裤 / 手持烤面包机）交叉检索 Fab，
**无任何成品角色与参考图完全一致** → 你的角色为专属概念设计，需用同品质资产替代/定制。

### 最接近的可替代角色
| 资产 | 匹配点 | 链接 |
|---|---|---|
| **Summer Girl — Modern Casual Character** | 双马尾 + 休闲背带装 + 头身 morph + 发色/服装换色 + 绑定动画，最贴近 | https://www.fab.com/listings/9ae82e06-cb21-4e35-ab7d-7904dc76c14a |
| **Stylized Anime Girl – Game Ready** | 高品质风格化少女，UE5/Unity 通用 | https://www.fab.com/listings/3d951bac-0f75-4ce4-a49a-1b73f6c73121 |
| **Stylized Hero Characters Pack vol.3** | 「英雄射击」定位（Overwatch/Valorant 可读性，3 英雄 × 9 皮肤） | https://www.fab.com/listings/370c4bc5-aa68-4fba-8f1a-800562e7faa1 |

### 100% 还原路径（商城无现成件时）
- 用现有角色三视图跑 **图生 3D**：`buddy-cloud.py 3d --image-url <三视图URL>`
- 或基底角色 `Summer Girl` + 定制兔耳帽配件 + 红背带裤换色

---

## 3. 武器道具 —— 角色手持的「烤面包机枪」

| 资产 | 匹配说明 | 链接 |
|---|---|---|
| **Stylized Rigged Toaster (带动画表情)** | 对应 demo「吐司子弹」设定的射击道具 | https://www.fab.com/listings/4f939be9-5320-4d8f-a756-9b97ca9a6ee3 |

---

## 推荐落地组合（最省成本复刻参考图）

1. **框架**：Narrative Pro 2（玩法底层）
2. **场景**：Stylized Christmas Amusement Park（= 场景原图）+ Minipoly 系列（微缩变体）
3. **角色**：Summer Girl 作基底 → 换红背带裤配色 + 加兔耳帽配件
4. **武器**：Stylized Toaster 作手持射击道具

> 若要严格 100% 还原参考图角色，走「图生 3D / 定制建模」。

---

## 4. 同级品质扩展参考（已验证 Narrative Pro 2 品质画像后扩展）

### 4.1 Narrative Pro 2 真实品质画像（核实）
| 维度 | 实情 |
|---|---|
| 发行商 | **Narrative Tools Inc.**（创始人 Reuben Ward，UE 编程十余年，YouTube 35 万订阅）|
| 工程档次 | **C++ 核心系统 + GAS（Gameplay Ability System）+ CommonUI** —— AAA 级工程化标志 |
| 完整度 | 战斗(Narrative Arsenal)/库存/任务/对话/同伴/AI-NPC/存档/开放世界/快速旅行 |
| 配套 | 含 Demo Map + 免费可玩 RPG Sample + "Relic Heist" 技术演示 |
| 口碑 | 4.4/5（74 评价）、Discord 约 8000 开发者 |

> **关键发现**：Narrative Pro 2 的演示关卡美术明确来自 **Leartes Studios、Polyphoria、PolySphere**。而 **Leartes Studios 正是场景图作者 StylArts 的母厂** —— 即官方框架本身就是搭配 Leartes/StylArts 美术做演示的。本项目「Narrative Pro 2 ＋ StylArts 游乐园」恰为官方同生态搭配，框架与美术天然兼容、不会割裂。

### 4.2 品质基准与扩展主线
> **品质基准 = C++/GAS 工程化框架 ＋ Leartes(StylArts) 生态风格化美术。**
> 沿「Narrative Tools 框架 ＋ Leartes/StylArts 美术」官方同生态线扩展，最稳。

**A. 玩法框架（同级 · GAS 工程）**
| 参考 | 同级理由 |
|---|---|
| GASP – Game Animation Sample（Epic 官方，免费）| UE5.5 官方动作样板，GAS 同源，可作射击手感底座 |
| Narrative Tools 同厂其他工具（`/sellers/Narrative Tools Inc.`）| 同作者同代码风格，无缝叠加 |
| Polyphoria / PolySphere 工程包 | 官方 Demo 同生态合作方，兼容性最高 |

**B. 场景（Leartes / StylArts 生态）**
| 参考 | 同级理由 |
|---|---|
| Dwarven Citadel Megapack — Leartes Studios | 同母厂旗舰 megapack，AAA 风格化 |
| The Carnival – Theme Park（67 网格，UE5.2-5.5）| 另一套嘉年华游乐园，可换皮 |
| Stylized Environment（100+ AAA 资产）| 风格化自然/户外拓展关卡 |

**C. 角色（风格化可爱英雄 · game-ready）**
| 参考 | 同级理由 |
|---|---|
| Stylized Character – Chibi Adventurer | Q 版大头身、2 英雄多变体 | 
| Synty 风格化角色合集（syntystore.com）| 与场景风格统一、量大价优 |
