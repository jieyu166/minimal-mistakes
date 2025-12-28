---
layout: single
title: "AI API 輔助判讀的原型設計"
date: 2024-02-03 09:00:00 +0800
categories: [AI 與工具]
tags: [OpenAI, Google Gemini, Workflow]
excerpt: "結合雲端大語言模型，協助生成報告草稿與臨床建議。"
---

將 OpenAI 與 Google Gemini API 整合進工作流程後，可以快速生成報告草稿，並針對不確定的診斷給出參考建議。我習慣先建立結構化輸入，把病史、影像所見與關鍵問題整理成表格，再將結果送入模型，以降低幻覺與不一致的風險。

目前的原型仍以醫師審閱為核心，AI 只做輔助。未來可望加入自動比對指南與文獻，讓建議更有依據。
