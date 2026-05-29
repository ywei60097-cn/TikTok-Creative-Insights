---
name: creative-insights
description: Search, validate, and synthesize popular Douyin/TikTok China AI ecommerce videos for creative strategy. Use when the user asks for Creative Insights, hot AI ecommerce videos, daily Douyin trend monitoring, category-by-category video examples, product video references, viral hooks, scripts, links, or inspiration for AI-generated ecommerce video production across categories such as appliances, photography, drones, food, apparel, beauty, home, pets, or digital products.
---

# Creative Insights

## Goal

Produce a concise, source-linked creative intelligence brief for AI ecommerce video production. Focus on videos or creator posts that are useful references for generating product-selling AI videos, not generic AI news.

## Core Workflow

1. Clarify scope only when the user omits a critical constraint such as market, date range, or output channel. Otherwise assume Douyin China, the last 24 hours for daily briefs, and Chinese output.
2. Search fresh sources first. Prefer direct Douyin pages, creator pages, platform hot lists, ecommerce creator communities, brand accounts, social search results, and reputable reposts that expose a usable video link.
3. Group candidates by product category. Use the taxonomy in `references/categories.md`; add a temporary category only when at least two useful examples do not fit.
4. Keep only entries with a working URL or a clearly attributable source page. Do not invent links, metrics, creators, brands, or timestamps.
5. Score each candidate with `references/scoring.md`. Prioritize examples that reveal a reusable creative pattern, not only high engagement.
6. Write the brief using `references/output-template.md`. Include category sections, video links, observed creative pattern, why it is useful for AI ecommerce generation, and a concrete remake angle.

## Evidence Rules

- Always verify whether links open or are at least discoverable from search snippets before including them.
- If exact Douyin metrics are unavailable, say `互动数据未公开/未核验` instead of estimating.
- If a link is a repost, label it as `二手来源` and include the original account or title when visible.
- Prefer 5-8 high-signal examples over long unfiltered lists.
- For daily automation, include a `数据不足` section when a category has no credible links that day.

## Search Strategy

Use multiple query patterns and rotate them to avoid a narrow feed:

- `site:douyin.com AI 电商 视频 产品 展示`
- `抖音 AI 商品视频 爆款`
- `抖音 AIGC 带货 视频 家电`
- `AI 生成 商品短视频 抖音 服饰`
- `无人机 AI 电商短视频 抖音`
- `食品 AI 带货 视频 抖音`

When web search is weak, broaden to creator/tool ecosystems and mark the source type:

- Douyin creator pages and search results
- Jianying/CapCut template pages
- Xiaohongshu/Bilibili posts discussing Douyin AI ecommerce examples
- Official brand accounts reposting Douyin videos
- Public case studies from creative tools or MCN accounts

## Daily Brief Defaults

- Time window: last 24 hours in Asia/Shanghai unless the user requests another range.
- Language: Chinese.
- Categories: appliances, photography, drones, food, apparel, beauty, home, pets, digital products.
- Output length: top 1-3 examples per active category, then cross-category patterns.
- End with 3-5 production recommendations for the user's AI ecommerce video generation workflow.

## References

- Read `references/categories.md` when deciding categories or keywords.
- Read `references/scoring.md` when ranking examples.
- Read `references/output-template.md` before writing a brief or automation prompt.
