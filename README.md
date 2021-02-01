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
clone 此專案，並以新建立的 branch 進行作答。請參考[設計稿](https://www.figma.com/file/Gvsqct4CKMYsHIrjTOT5FA/For-interview?node-id=0%3A1)實作以下功能：

1. 可以切換背板 / 邊框模式
2. 透過 local API server 取得資料
3. 透過 dropdown 切換裝置與產品資訊
4. 點擊加入購物車時，將產品資料存入 `cartItems` ，並使用 `console.log` 印出 `cartItems` 內容