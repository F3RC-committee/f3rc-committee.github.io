---
title: ご観覧について
sort: 2
layout: default
---

## お知らせ
- 2025年度大会の詳細を公開しました。
- [2024年度大会の実施状況について確認したい方はこちら](/過去の大会/2024/attend.html)
- [2023年度大会の実施状況について確認したい方はこちら](/過去の大会/2023/attend.html)

{% assign source_page = site.pages | where: "path", "F3RC2025/attend.md" | first %}

{{ source_page.content | markdownify }}