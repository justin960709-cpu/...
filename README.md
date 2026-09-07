# 換物 HuanWu

可直接部署至 Render 的二手交易平台前端原型。包含商品瀏覽、分類搜尋、刊登商品、購物車、結帳與物流方式選擇。

## Render 部署

1. 將本資料夾推送到自己的 GitHub repository。
2. 在 Render 選擇 **New + → Blueprint**，連結該 repository（會自動讀取 `render.yaml`）；或建立 Web Service，Start Command 設為 `node server.js`。
3. Render 會提供公開網址。

## 正式上線前

目前商品、購物車與訂單皆保存在瀏覽器 localStorage，適合展示與前端驗證。正式交易須加入：帳號驗證、資料庫、金流（例如綠界／藍新）、物流 API（7-ELEVEN、全家、黑貓）及伺服器端訂單驗證。
