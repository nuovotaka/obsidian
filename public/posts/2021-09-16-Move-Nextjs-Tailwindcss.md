---
title: 'Next.jsとTailwind CSSに移行しました'
description: Nextjs Tailwind css Netlify Typescript Eslint
date: '2021-09-16'
modified_date: '2022-05-22'
image: /assets/images/posts/nextjs-starter-banner.png
---

## HugoからNextjsとTailwind CSSを使ったサイトへ移行

[Hugo](https://gohugo.io/)から[Next js](https://nextjs.org/)と[Tailwind CSS](https://tailwindcss.com/)を使ったサイトへ移行しました。
記事はマークダウンで管理をしていてこれまでの流れを踏襲しています。

```Next.js```はReactをベースにしたフロントエンドフレームワークです。
SSG(Static Site Generation)やSSR(Server Side Rendering)ができます。

### 参考githubファイル
[Next-js-Blog-Boilerplate](https://github.com/ixartz/Next-js-Blog-Boilerplate)

### Next.jsをアップデートしたファイル
```Next.js```ファイルを10から11へとアップデートしました。
このサイト自身のファイルが参考ファイルになります。(2022/05/22)

~~[Home_Site_Nextjs_2021](https://github.com/nuovotaka/home_site_nextjs_2021)~~

[Home_Site_Nextjs_2022](https://github.com/nuovotaka/home_site_nextjs_2022)

### 記事とアプリケーションの分離を行いました
変更は下記に行いました。すでにマージしてあります。
[github_api](https://github.com/nuovotaka/home_site_nextjs_2021/tree/github-api)
netlifyからBuild hookのurlを設定してもらいgithubでwebhookにそのurlを設定しました。
