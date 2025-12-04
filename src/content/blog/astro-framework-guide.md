---
title: 'Astro 5：為內容而生的極速框架'
description: '深入解析為什麼我們選擇 Astro 作為建構高效能網站的首選框架，以及它如何改變網頁開發的遊戲規則。'
pubDate: '2025-12-03'
heroImage: '/images/service-frontend.png'
tags: ['Dev', 'Astro', 'Performance']
---

在前端框架百家爭鳴的時代，**Astro** 以黑馬之姿異軍突起。它不是要取代 React 或 Vue，而是要重新定義「內容網站」的建構方式。

## 核心理念：Islands Architecture (孤島架構)

Astro 最具革命性的設計就是 **Islands Architecture**。

傳統的 SPA (單頁應用) 會將大量的 JavaScript 打包傳送到瀏覽器，導致初次載入變慢 (Hydration)。Astro 則採取了完全不同的策略：

1. **預設為靜態 HTML**：Astro 預設會移除所有 JavaScript，只傳送純 HTML 與 CSS。這保證了最快的載入速度。
2. **按需載入互動元件**：只有當頁面上的某個區塊（如圖片輪播、購物車按鈕）真正需要互動時，Astro 才會載入該區塊所需的 JavaScript。這些區塊就像靜態海洋中的「互動孤島」。

## 為什麼這很重要？

對於部落格、形象官網、文件站這類以「內容」為主的網站來說，90% 的內容都是靜態的。為了那 10% 的互動功能而犧牲整體的效能，是不划算的。

Astro 讓我們魚與熊掌兼得：
- **擁有靜態網站的極致效能 (Lighthouse 100分)**
- **同時具備現代框架的開發體驗 (React/Vue 元件)**

## 鈦宇數位的實踐

在 **鈦宇數位**，我們全面採用 Astro 5 來建構客戶的形象網站。這讓我們能夠交付出視覺效果驚人，同時在 Google PageSpeed 上獲得滿分的網站。

這不僅是技術的選擇，更是對使用者體驗的承諾。
