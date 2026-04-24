# 按平台导航

这个页面按模型平台来索引仓库内容，方便把同一类 prompt 迁移到不同生成器中使用。

## GPT Image

适合：
- 直接用自然语言写完整 prompt
- 强调文字、排版、信息图、UI、海报构图
- 适合中英文完整句子

优先入口：
- [USE-CASES.md](./USE-CASES.md)
- [advanced/PROMPT-TEMPLATES.md](./advanced/PROMPT-TEMPLATES.md)
- [movie-posters/PROMPT-TEMPLATES.md](./movie-posters/PROMPT-TEMPLATES.md)
- [ui/PROMPT-TEMPLATES.md](./ui/PROMPT-TEMPLATES.md)

## Midjourney

适合：
- 强风格化画面
- 角色、场景、海报感视觉
- 更偏关键词式压缩表达

改写建议：
- 把长句压缩成 `主体 + 场景 + 风格 + 光线 + 色彩 + 构图`
- 把“不需要什么”精简成少量排除项
- 可从这些目录取材：
  - [advanced/TOP-10.md](./advanced/TOP-10.md)
  - [anime/TOP-10.md](./anime/TOP-10.md)
  - [movie-posters/TOP-10.md](./movie-posters/TOP-10.md)

## Flux

适合：
- 写实图、商业图、产品图、海报图
- 在保留自然语言描述的同时做风格控制

优先入口：
- [ecommerce/PROMPT-TEMPLATES.md](./ecommerce/PROMPT-TEMPLATES.md)
- [portraits/PROMPT-TEMPLATES.md](./portraits/PROMPT-TEMPLATES.md)
- [movie-posters/PROMPT-TEMPLATES.md](./movie-posters/PROMPT-TEMPLATES.md)

## SDXL

适合：
- 需要结构化、模块化 prompt 的场景
- 适合拆成正向 prompt / 风格词 / 负面词

改写建议：
- 先从本仓库模板取“正向主体描述”
- 再补风格、光线、镜头、材质
- 最后再单独补 negative prompt

优先入口：
- [advanced/PROMPT-TEMPLATES.md](./advanced/PROMPT-TEMPLATES.md)
- [anime/PROMPT-TEMPLATES.md](./anime/PROMPT-TEMPLATES.md)
- [ecommerce/PROMPT-TEMPLATES.md](./ecommerce/PROMPT-TEMPLATES.md)

## 推荐对照关系

- 海报: `movie-posters` 最适合 GPT Image / Flux / Midjourney
- 人像: `portraits` 最适合 GPT Image / Flux / SDXL
- 产品: `ecommerce` 最适合 GPT Image / Flux / SDXL
- UI: `ui` 最适合 GPT Image
- 动漫: `anime` 最适合 Midjourney / SDXL / GPT Image
- 通用骨架: `advanced` 适合全部平台

