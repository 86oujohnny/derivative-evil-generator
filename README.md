# 微分作業產生器：邪惡版

一個純前端、可重現、附完整詳解的微分題目產生器。題目可以狠，定義不能含糊。

## 功能

- 五種邪惡度：從「尚有良知」到「Reviewer 2」
- 以 seed 重現同一份作業
- 預設依完整配額產生 20 題
- 支援 sum/difference、product、quotient、chain rule
- 支援 logarithmic、implicit、parametric differentiation
- 支援 higher derivatives、symmetry、recursion 與 special-point evaluation
- 每題包含完整詳解、定義域與常見陷阱
- 使用 MathJax 顯示印刷式數學公式
- 可列印或儲存成 PDF
- 不需要伺服器；所有出題都在瀏覽器內完成

## 本機使用

直接以瀏覽器開啟 `index.html`。公式由 MathJax CDN 載入，因此需要網路連線。

## 部署至 GitHub Pages

1. 在 GitHub 建立新的 repository，例如 `derivative-evil-generator`。
2. 將本資料夾內的檔案上傳至 repository 根目錄。
3. 開啟 **Settings → Pages**。
4. 在 **Build and deployment** 選擇：
   - Source：`Deploy from a branch`
   - Branch：`main`
   - Folder：`/ (root)`
5. 儲存並等待部署完成。

網站網址通常會是：

```text
https://YOUR-USERNAME.github.io/derivative-evil-generator/
```

## 專案結構

```text
derivative-evil-generator/
├── index.html
└── README.md
```

## 隱私

題目、seed 與詳解皆在使用者的瀏覽器中處理，不會上傳作答內容。

## 技術

- HTML / CSS / Vanilla JavaScript
- MathJax 3

## 授權

尚未指定開源授權。在加入 LICENSE 前，原作者保留所有權利。
