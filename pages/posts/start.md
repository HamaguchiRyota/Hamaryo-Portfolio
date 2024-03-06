---
title: ポートフォリオページ公開
date: 2024/3/6
description: 環境構築からページ作成まで
tag: blog
author: Ryota Hamaguchi
---

## 作成の流れ
Next.jsの公式サイトにたくさんの[テンプレート](https://vercel.com/templates/next.js)が用意されています。<br>
その中から[Portfolio Starter Kit](https://vercel.com/templates/next.js/portfolio-starter-kit)というのを選択しました。<br>
Next.js上でnextraというライブラリを使用したテンプレートのようです。

## 苦戦したところ
**yarn**か**npm**を使用してページを表示させているのですが、そのどちらかのインストールを忘れており、
**(yarn) or (npm) run dev**
を実行してもエラーを吐いてしまうことがありました。