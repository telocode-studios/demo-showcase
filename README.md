# Side Projects Demo

新創競賽三個 side project 的展示頁，使用 GitHub Pages 託管。

## 線上網址

部署後網址：`https://pyycode2037.github.io/demo-showcase/`

## 如何更新內容

直接編輯 `index.html`，commit 並 push 後，GitHub Pages 會自動更新（網址不變）。

常見要補的東西：

- **影片**：把對應 `<div class="video">` 裡的「影片準備中」換成 YouTube 嵌入碼
  ```html
  <iframe src="https://www.youtube.com/embed/影片ID" allowfullscreen></iframe>
  ```
- **連結**：把 `href="#"` 換成實測網址、GitHub repo、說明文件網址
- **文字**：替換「專案名稱」與「待補充」描述

更新指令：

```bash
git add -A && git commit -m "update demo content" && git push
```
