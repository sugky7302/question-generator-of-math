<h1 align=center>QUESTION GENERATOR of MATH</h1>
這是用來生成數學題目的 Python 專案，透過 Flask 和 Jinja2 把題目以網頁呈現，然後使用 pdf 套件輸出成 .pdf 放在 Google Drive 裡。

## 安裝
直接使用 vscode 的 container 套件把環境建置起來，接著輸入以下指令：
```sh
# 進入 root 模式
sudo su

# 關閉 Poetry 強制使用虛擬環境的功能
poetry config virtualenvs.create false

# 添加套件
poetry add flask
```