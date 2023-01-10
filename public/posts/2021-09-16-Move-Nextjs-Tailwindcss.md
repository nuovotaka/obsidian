---
title: "Next.jsとTailwind CSSに移行しました"
description: Nextjs Tailwind css Netlify Typescript Eslint
created: "2021-09-16"
updated: "2022-05-22"
---

## Hugo から Nextjs と Tailwind CSS を使ったサイトへ移行

[Hugo](https://gohugo.io/)から[Next js](https://nextjs.org/)と[Tailwind CSS](https://tailwindcss.com/)を使ったサイトへ移行しました。
記事はマークダウンで管理をしていてこれまでの流れを踏襲しています。

`Next.js`は React をベースにしたフロントエンドフレームワークです。
SSG(Static Site Generation)や SSR(Server Side Rendering)ができます。

### 参考 github ファイル

[Next-js-Blog-Boilerplate](https://github.com/ixartz/Next-js-Blog-Boilerplate)

### Next.js をアップデートしたファイル

`Next.js`ファイルを 10 から 11 へとアップデートしました。
このサイト自身のファイルが参考ファイルになります。(2022/05/22)

~~[Home_Site_Nextjs_2021](https://github.com/nuovotaka/home_site_nextjs_2021)~~

[Home_Site_Nextjs_2022](https://github.com/nuovotaka/home_site_nextjs_2022)

### 記事とアプリケーションの分離を行いました

変更は下記に行いました。すでにマージしてあります。
[github_api](https://github.com/nuovotaka/home_site_nextjs_2021/tree/github-api)
netlify から Build hook の url を設定してもらい github で webhook にその url を設定しました。
