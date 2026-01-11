---
index: 100
title: '4-Hour Extreme Refactoring: Returning to Astro for Performance Optimization'
description: Documenting the migration from Solid-start back to Astro 5.0. With Zen Code (Gemini 3 Flash), we corrected architectural mistakes and finished 60% of the task in just 4 hours.
article:
    authors:
        - Jiang Xiayao
    section: Performance
    tags:
        - Astro
        - Zen Code
        - Solid-start
        - Refactoring
        - AI
    pubDate: 2026-01-11
    image: 'https://ik.imagekit.io/chinesefonts/tr:w-1200/image/photo-1451187580459-43490279c0fa.jfif'
---

# 🚀 4-Hour Extreme Refactoring: Returning to Astro for Performance Optimization

In technology, a single deviation in architecture often costs several times more to correct. In the latest refactoring of the **Chinese Font Plan**, we completed a "strategic retreat" from a non-production-ready framework back to a mature ecosystem.

## 🏗️ Reflection: The SSR Mistake

Previously, we migrated the project from Astro to `Solid-start (Solid.js + Vinxi)`. We were lured by the promise of full-stack SSR, but reality hit hard.

**Let's be blunt: Solid-start is far from being a production-ready framework.**

Throughout its use, we encountered numerous issues stemming from SSR: Hydration Mismatches, unstable middleware behavior, and constant runtime errors on static hosting platforms. For a project targeting ultimate loading performance, this immature architecture was a nightmare.

Migrating to a non-production-ready framework was a major mistake. Returning to **Astro 5.0**, with its mature SSG and Islands Architecture, is the correct path for performance optimization.

## 🤖 Zen Code: The Heavy Lifter

While the direction was clear, the volume of code for a cross-framework migration was massive. This is where **[Zen Code](https://github.com/KonghaYao/zen-code)**, powered by **Gemini 3 Flash Preview**, showed its incredible efficiency.

### 1. How It Helped
Zen Code did more than just autocomplete; it handled the most painful parts of the migration:

*   **Fixing SSR Logic**: It helped me decouple chaotic Server Actions into Astro frontmatter and client-side Islands, completely eliminating hydration errors.
*   **Automated Route Refactoring**: It mapped complex API routes back to Astro's static or server endpoints.
*   **Performance-Driven Styling**: It assisted in the full atomic conversion from Less to Tailwind CSS.

### 2. The Results
*   **AI Contribution**: ~**60%** of code changes were AI-generated.
*   *Total Time**: 4 hours to migrate core functionality.
*   **Performance Gain**: After returning to Astro, the removal of unnecessary runtime JS kept Lighthouse scores at 100/100 and reduced the build size by ~30%.

## 💰 The Cost of Efficiency

Efficiency comes with a cost. This refactoring cost **$6.6** in API fees.

Model pricing remains expensive for large-scale context reads. Gemini 3 Flash Preview is fast, but without efficient caching, frequent rewrites cause the bill to rise quickly.

However, considering it corrected an architectural mistake that would have taken days in just 4 hours, the ROI of $6.6 is still excellent.

## 💡 Summary & Advice

1.  **Avoid Non-Production Frameworks**: For core business, mature ecosystems (like Astro) matter more than novel concepts.
2.  **AI is a Refactoring Powerhouse**: For cross-architecture "heavy lifting," tools like Zen Code save 80% of repetitive labor.
3.  **Embrace Islands**: For high-performance web apps, Astro's partial hydration remains the best solution.

---

**Driven by [Zen Code](https://github.com/KonghaYao/zen-code), returning to ultimate performance.**
