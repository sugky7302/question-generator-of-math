<div style="display:flex; flex-direction: column; align-items: center">
    <p style="font-size: 2rem; font-weight: 600">QUESTION GENERATOR of MATH</p>

![standard-readme compliant](https://img.shields.io/npm/v/@angular/core.svg?logo=npm&logoColor=fff&label=NPM+package&color=limegreen)

這是用來生成數學題目的 Qwik + PartyTown 專案，透過簡易的網頁把題目以 html 呈現，然後使用 pdf 套件輸出成 .pdf 放在 Google Drive 裡。
</div>



## 目錄
- [安裝](#安裝)
- [使用](#使用)

## 專案架構
```
├── public/ 影音檔或圖片
│   └── ...
└── src/
    ├── components/ 共享組件
    │   └── ...
    └── routes/ 路由組件
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