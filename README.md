# interview-ts

## Project setup
```
# Install dependencies
yarn install

# Compiles and hot-reloads for development
yarn serve

# Run mock API server
yarn serve:db
```

## 規則
* 作答時間為 2 小時
* 繳交方式：收到題目 3 天內，將 repository URL 寄回
* 針對題目若有任何疑問，也可以來信詢問

## 題目
clone 此專案，並以新建立的 branch 進行作答。請參考[設計稿](https://www.figma.com/file/Gvsqct4CKMYsHIrjTOT5FA/For-interview?node-id=0%3A1)與[互動原型](https://www.figma.com/proto/Gvsqct4CKMYsHIrjTOT5FA/For-interview)來實作以下功能：

1. 透過 local API server 取得資料（執行 `yarn serve:db` ）
2. 使用者可以透過下拉式選單切換**裝置（device）**
3. 使用者可以選擇 **邊框樣式（case color）** 與 **背板樣式（backplate style）** 並且點擊樣式預覽
4. 使用者可以選擇以 **背板模式（standard）** 或 **邊框模式（bumper）** 進行預覽
5. 使用者可以選擇 **手機顏色** 進行預覽
6. 點擊加入購物車時，將使用者所選擇的產品資料存入 `cartItems` ，並使用 `console.log` 印出 `cartItems` 內容