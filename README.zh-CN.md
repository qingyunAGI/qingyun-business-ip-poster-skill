# Qingyun 高级商务个人 IP 海报 Skill

<p align="center">
  <strong>把 3—5 张人物参考照与一段自然语言需求，转化为 5 / 7 / 10 张真正有差异的高级商务个人 IP 海报。</strong>
</p>

## 5 张用户认可效果图

<p align="center">
  <strong>3 张人物身份参考 + 1 段自然语言文案 → 10 个方向探索 → 5 张认可版本 → 1 个可复用 Skill</strong>
</p>

<p align="center">
  <img src="showcase/01-black-neon-green.png" width="31%" alt="黑底荧光绿峰会型海报">
  <img src="showcase/02-ivory-editorial.png" width="31%" alt="暖象牙白企业顾问型海报">
  <img src="showcase/03-graphite-thought-leader.png" width="31%" alt="石墨灰思想领袖型海报">
</p>

<p align="center">
  <img src="showcase/04-high-contrast-closeup.png" width="46%" alt="极黑超近景强识别海报">
  <img src="showcase/05-black-gold-authority.png" width="46%" alt="黑金权威背书型海报">
</p>

<p align="center">
  <strong>⭐ 如果这个工作流对你的创作有帮助，请点击仓库右上角的 Star。</strong><br>
  每一颗 Star 都会帮助更多创作者发现、使用并共同完善这套开放工作流。
</p>

<p align="center">
  <a href="https://github.com/qingyunAGI/qingyun-business-ip-poster-skill">
    <img alt="给项目点 Star" src="https://img.shields.io/badge/%E2%AD%90-%E7%BB%99%E9%A1%B9%E7%9B%AE%E7%82%B9_Star-FFD54F?style=for-the-badge&logo=github&logoColor=111111">
  </a>
</p>

<p align="center">
  <a href="README.md">English</a> ·
  <a href="#安装方法">安装方法</a> ·
  <a href="#5-张用户认可效果图">效果展示</a> ·
  <a href="https://github.com/qingyunAGI/qingyun-business-ip-poster-skill/releases/latest">最新版本</a>
</p>

<p align="center">
  <img alt="版本 1.0.0" src="https://img.shields.io/badge/version-1.0.0-C8A66A">
  <img alt="Codex Skill" src="https://img.shields.io/badge/Codex-Skill-111111">
  <img alt="海报比例 3:4" src="https://img.shields.io/badge/poster-3%3A4-4B5D36">
  <img alt="中英双语文档" src="https://img.shields.io/badge/docs-English%20%7C%20中文-E8E1D3">
</p>

`qingyun-business-ip-poster-skill` 是一个面向 Codex 的高级商务个人 IP 海报工作流。它会把零散文案与多张人物参考照整理成结构化设计任务，批量生成竖版 3:4 方案，并重点控制人物一致性、标题可读性、事实准确性与版本差异。

它不是给同一张模板换 10 次颜色，而是主动变化镜头、姿态、人物位置、背景场景、标题结构、信息分栏、强调色和视觉叙事，再逐张完成质量检查。

## 它能做什么

- 用一条简洁引导帮助用户准备真正必要的素材。
- 把自然语言文案编译成结构化海报信息卡。
- 把多张人物照作为身份锚点，而不是普通风格参考。
- 一次生成 **5 / 7 / 10 张**差异明显的竖版 3:4 方案。
- 原样保护姓名、身份、履历、数字与必须保留的文字。
- 使用克制的国际商业杂志与思想领袖视觉系统。
- 检查人脸、文字、事实、肢体、缩略图可读性、裁切安全区与批次差异。
- 从整组方案中推荐 1—3 张继续定向精修。

## 生成数量怎么选

| 数量 | 适合情况 | 建议 |
| --- | --- | --- |
| **5 张** | 时间有限，快速探索主要方向 | 适合轻量测试 |
| **7 张** | 兼顾多样性与筛选效率 | **默认推荐** |
| **10 张** | 先建立更大的样本池，再挑 1—3 张精修 | **重要项目强烈推荐** |

如果用户说“直接做”但没有选择数量，Skill 默认生成 **7 张**。

## 推荐 Codex 模型设置

在当前最新版 Codex 中，推荐按以下方式使用：

1. 对话模式选择 **ChatGPT 聊天**。
2. 首选 **GPT-5.6 · 高**，综合效果最佳。
3. **GPT-5.5 · 高** 的效果也很不错。
4. 进入正式出图阶段时，点选 **生成图片**。

以上是为了获得更好效果的推荐设置，不是 Skill 的安装硬依赖；模型和界面选项名称可能随 Codex 版本更新。

## 素材准备

### 必需素材

1. **人物形象照 3—5 张**
   - 至少 1 张清晰正脸
   - 最好再有 1 张半身照
   - 如有侧面、思考、演讲或工作场景照，一并提供
2. **主标题或核心主题**
3. **姓名**

### 推荐素材

- 一句话身份定位
- 3—5 条可核验的核心背书
- 1 个最值得强调的数字、结论或关键词
- 发布平台
- Logo、活动名称、时间、地点、品牌色、禁用色

### 默认设置

- 比例：竖版 **3:4**
- 建议尺寸：**1080 × 1440**
- 平台：视频号、小红书、抖音等社交媒体
- 风格：高级商务杂志 / 思想领袖人物海报
- 数量：**7 张**

## 使用流程

1. **素材确认**：核对人物照、文案、比例、平台与生成数量。
2. **内容编译**：整理主标题、姓名、身份、背书、强调点和必须原样保留的文字。
3. **版本矩阵**：为每张分配不同的场景、镜头、姿态、版式、色彩和强调方式。
4. **批量生成**：为每个版本编写独立指令，并把用户照片作为身份参考。
5. **逐张质检**：检查人脸、文字、事实、肢体、可读性、裁切与真实差异。
6. **筛选精修**：从整组中推荐 1—3 张，对人脸、排版、色彩与背景做定向优化。

## 核心视觉体系

| 方向 | 视觉语言 | 适用主题 |
| --- | --- | --- |
| 黑底 + 荧光绿 | 峰会动势、强标题、低对比舞台环境 | 趋势判断、强观点传播 |
| 暖象牙白 + 黑侧栏 | 编辑式分栏、墨绿强调、稳重半身人像 | 顾问、讲师、专家介绍 |
| 石墨灰 + 信号黄 | 克制坐姿、减少背书、强调深度观点 | 长期主义、人物访谈 |
| 极黑超近景 | 人脸主导、标题压顶、极少几何元素 | 短视频封面、IP 栏目 |
| 黑色 + 香槟金 | 对称权威、克制光晕、正式层级 | 大会嘉宾、年度演讲、里程碑 |

在 7 张或 10 张模式下，还会加入会议桌决策者、建筑空间企业家、峰会演讲与极简人物专访等方向。每张只使用一种强调色，只突出一个关键词、数字或结论。

## 示例提示词

```text
请用这 4 张人物照做 7 张竖版 3:4 高级商务个人 IP 海报。
主标题是“为什么 AI Worker 类产品都在盯着企业打”。
姓名、身份和履历必须原样保留；镜头、姿态、人物位置、场景和标题结构要明显不同。
完成后先推荐最值得精修的 2 张。
```

```text
请先引导我准备人物照片和海报文案。我想做 10 张企业顾问个人 IP 海报，
适合视频号和小红书，整体克制、可信、有国际商业杂志感。
```

```text
基于这些照片先快速探索 5 个方向。每张只能有一种强调色；
出现人脸漂移、中文错字、虚构 Logo、手部畸形或版式重复时，必须先修复再交付。
```

## 质量标准

同时满足以下条件，才算达到交付标准：

- 人物仍然是本人，脸型、五官、年龄感和显著特征没有漂移。
- 姓名、标题、身份、履历、数字与用户提供的内容一致。
- 海报缩小到手机缩略图后，仍能第一眼读出核心标题。
- 画面只有一个视觉中心和一个主要强调点。
- 重要文字不贴边，不落入平台裁切危险区。
- 手部、服装、麦克风与人物比例自然。
- 不虚构用户没有提供的客户、奖项、大会、Logo 或品牌。
- 批量差异不只来自换色，镜头、姿态、位置、场景、版式和强调方式都应变化。
- 整体像商业杂志人物封面，而不是廉价课程促销模板。

凡是出现人脸不像本人、关键文字错误、肢体畸形、虚构信息、层级不可读或与其他版本高度相似的方案，都应先修复再交付。

## 适用场景

- 个人 IP、专家与顾问人物海报
- 创始人、企业家、讲师、嘉宾介绍
- 视频号、小红书、抖音封面
- 峰会、论坛、演讲、访谈宣传
- 课程讲师与知识产品推广
- 思想领袖栏目与强观点内容
- 商业案例、职业里程碑与品牌人物展示

## 安装方法

### 方法 A：下载发布包

直接下载 [`qingyun-business-ip-poster-skill-1.0.zip`](qingyun-business-ip-poster-skill-1.0.zip)，或前往 [GitHub Releases](https://github.com/qingyunAGI/qingyun-business-ip-poster-skill/releases/latest) 获取最新版。

解压后，把 Skill 放进 Codex 的 skills 目录。安装时建议把文件夹改名为与 Skill ID 一致：

**Windows PowerShell**

```powershell
Expand-Archive .\qingyun-business-ip-poster-skill-1.0.zip .
New-Item -ItemType Directory -Force "$env:USERPROFILE\.codex\skills" | Out-Null
Move-Item .\qingyun-business-ip-poster-skill-1.0 `
  "$env:USERPROFILE\.codex\skills\qingyun-business-ip-poster-skill-1-0"
```

**macOS / Linux**

```bash
unzip qingyun-business-ip-poster-skill-1.0.zip
mkdir -p ~/.codex/skills
mv qingyun-business-ip-poster-skill-1.0 \
  ~/.codex/skills/qingyun-business-ip-poster-skill-1-0
```

安装后重启 Codex，或重新加载 Skills。

### 方法 B：克隆仓库

```bash
git clone https://github.com/qingyunAGI/qingyun-business-ip-poster-skill.git
```

把仓库中的 `qingyun-business-ip-poster-skill-1.0/` 复制到 Codex skills 目录，并改名为 `qingyun-business-ip-poster-skill-1-0`。

## 目录结构

```text
qingyun-business-ip-poster-skill/
├── README.md
├── README.zh-CN.md
├── qingyun-business-ip-poster-skill-1.0.zip
├── qingyun-business-ip-poster-skill-1.0/
│   ├── SKILL.md
│   ├── agents/
│   │   └── openai.yaml
│   └── references/
│       ├── design-system.md
│       ├── failure-modes.md
│       ├── intake-guide.md
│       ├── prompt-compiler.md
│       ├── quality-checklist.md
│       └── version-matrix.md
└── showcase/
    ├── 01-black-neon-green.png
    ├── 02-ivory-editorial.png
    ├── 03-graphite-thought-leader.png
    ├── 04-high-contrast-closeup.png
    └── 05-black-gold-authority.png
```

## 作者介绍

**彭青云（Kaiwen）**，AI 内容创作者、AI 短剧导演、AI 培训讲师与内容生产力架构师。长期关注 AI 视频、个人 IP、视觉叙事，以及如何把反复出现的创作实践沉淀为可复用的 Codex Skills、提示词和生产工作流。

GitHub：[@qingyunAGI](https://github.com/qingyunAGI)

---

本仓库发布 Skill **1.0.0** 版本与 5 张已认可效果图。仓库暂未附带开源许可证；如需转载、二次分发或商业打包，请先联系作者。
