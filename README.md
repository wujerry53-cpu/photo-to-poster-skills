# Photo to Poster Skills

Open-source AI prompts and Agent Skills for turning everyday photos into high-end editorial design posters.

目前包含两套独立玩法：

1. **Photo × Abstract Editorial Poster**  
   原始摄影 × 极简几何抽象重构

2. **Photo × Retro Hand-Drawn Poster**  
   原始摄影 × 复古手绘编辑插画

---

## Preview

### 01. Abstract Editorial Poster

适合：
- 建筑摄影
- 城市街拍
- 旅行照片
- 风景
- 静物
- 具有明显轮廓与结构的照片

核心效果：
- 保留原始摄影质感
- 提取主体轮廓、结构与代表性色彩
- 使用几何色块、细线与留白进行抽象重构
- 整体接近现代艺术展览、建筑平面设计与 Editorial Design

### 02. Retro Hand-Drawn Poster

适合：
- 日常随手拍
- 风景
- 花卉植物
- 烟花
- 街景
- 建筑
- 旅行照片

核心效果：
- 上半部分保留原始摄影
- 下半部分重新解释成复古手绘编辑插画
- 混合水彩、水粉、彩铅、油画棒、干刷与纸张肌理
- 具有旅行画册、复古绘本和艺术出版物的感觉

---

## Quick Start

最简单的使用方式：

1. 上传一张照片到支持图片理解和图片生成/编辑的 AI。
2. 打开 `prompts/`。
3. 选择对应 Prompt。
4. 复制完整 Prompt 并发送。
5. 等待 AI 生成最终海报。

建议一次只上传一张照片。

---

## Repository Structure

```text
photo-to-poster-skills/
├── README.md
├── LICENSE
├── prompts/
│   ├── abstract-editorial-poster.md
│   └── retro-handdrawn-poster.md
├── skills/
│   ├── photo-abstract-editorial-poster/
│   │   └── SKILL.md
│   └── photo-retro-illustration-poster/
│       └── SKILL.md
└── examples/
    ├── abstract-editorial/
    │   └── README.md
    └── retro-illustration/
        └── README.md
```

---

## Prompt or Skill?

如果只是想马上使用：

**直接复制 `prompts/` 里的 Prompt。**

如果你使用支持 Agent Skills 的 Agent：

**安装 `skills/` 里的对应 Skill。**

Prompt 是一次性的完整指令；Skill 更适合长期复用，让 Agent 在匹配到相关任务时按照既定工作流执行。

---

## Installation

### Generic Agent Skill

将需要的 Skill 文件夹复制到你所使用 Agent 的 Skills 目录。

例如：

```text
skills/
└── photo-retro-illustration-poster/
    └── SKILL.md
```

不同 Agent 的 Skill 安装路径和调用方式可能不同，请以当前产品文档为准。

---

## Usage Examples

### Retro Hand-Drawn

上传照片后：

```text
Use the photo-retro-illustration-poster skill on this image.
```

或直接复制：

```text
prompts/retro-handdrawn-poster.md
```

### Abstract Editorial

上传照片后：

```text
Use the photo-abstract-editorial-poster skill on this image.
```

或直接复制：

```text
prompts/abstract-editorial-poster.md
```

---

## Notes

- 生成式图片具有随机性，同一张照片多次生成可能产生不同结果。
- 尽量使用主体明确、构图完整、分辨率较高的原图。
- 如果原图包含人物，建议优先要求保留人物比例、姿态和身份特征，不要重绘上半部分。
- 如果第一次生成偏离原图，可要求仅重做插画区域，而不是重新生成整张照片。
- 本项目不保证不同模型之间生成效果完全一致。

---

## License

MIT License.

你可以自由使用、修改和分享这些 Prompt / Skill。  
如果你基于它们进行了明显改造或二次发布，欢迎保留项目来源说明。

---

## Author

Created by Jerry.

如果你在小红书看到这个项目：完整 Prompt 与 Skill 都在这个仓库里，可以直接复制或下载使用。
