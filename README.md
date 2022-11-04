<div style="display:flex; flex-direction: column; align-items: center">
    <p style="font-size: 2rem; font-weight: 600">QUESTION GENERATOR of MATH</p>

<div style="display: flex">
    <img style="margin-right: 10px" src="https://img.shields.io/badge/Node.js-v16.18.0-limegreen" alt="" />
    <img style="margin-right: 10px" src="https://img.shields.io/badge/NPM package-8.19.2-limegreen" alt="" />
    <img src="https://img.shields.io/badge/lang-Qwik-yellow" alt="" />
</div>

<br/>

這是用來生成數學題目的 Qwik + PartyTown 專案，透過簡易的網頁把題目以 HTML 呈現，然後使用 PDF 套件輸出成 .pdf 放在 Google Drive 裡。
</div>

## 目錄
- [專案架構](#專案架構)
- [安裝](#安裝)
- [使用](#使用)
- [參考](#參考)

## 專案架構
```
├── public/ 影音檔或圖片
│   └── ...
└── src/
    ├── components/ 共享組件
    │   └── router-head/ 自動讀取程式裡的 meta、link、.css 檔
    └── routes/ 路由組件
        ├── layout.tsx: 網站佈局
        ├── index.tsx: 首頁
        └── plus/: 加法
            └── index.tsx: 加法的頁面，路由為 /plus
```

## 安裝
直接使用 vscode 的 container 套件把環境建置起來，接著輸入以下指令：
```sh
# 安裝 pnpm 工具
npm install -g pnpm

# 進入專案
cd qwik-app

# 安裝所有依賴包
pnpm install
```

## 使用
- 如果是要開發，請啟動測試環境。
```sh
pnpm run start
```
- 如果是要部署，請啟動生產環境。
```sh
pnpm run preview

或

pnpm run build
```

## 參考
- [Qwik 官方指南](https://qwik.builder.io/docs/overview/)
- [PartyTown 說明手冊](https://partytown.builder.io/getting-started)