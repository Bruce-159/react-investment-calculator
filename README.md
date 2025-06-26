#React Investment Calculator  
[🔗 GitHub 部署頁面](https://bruce-159.github.io/react-investment-calculator/)

這是一個使用 React 製作的投資報酬試算工具，作為我學習 React 過程中的第二個練習專案。此專案強化了我對於表單輸入、狀態提升、雙向綁定、動態內容渲染與資料衍生運算等核心觀念的理解。

此專案涵蓋以下 React 關鍵技術與開發觀念：  
  
Derived Values（衍生值計算）  
所有投資回報皆根據輸入資料即時計算，不重複儲存狀態，避免不一致問題，且計算邏輯封裝在純函式中，易於測試與重複使用  

Two-Way Binding（雙向綁定）  
使用者在 UserInput 中的輸入會即時更新 state，實現輸入框與狀態的同步  

Lifting State Up（狀態提升）  
使用者輸入的數值狀態從 UserInput 提升至 App 元件，使計算邏輯與結果顯示可以共用資料來源  

Conditional Rendering（條件渲染）  
使用條件邏輯控制結果顯示區塊，避免在未輸入資料時渲染報表  
  

##預覽畫面

![image](https://github.com/user-attachments/assets/49afc1d9-d967-4286-9c75-50a80ef2d1c3)

---

## 功能特色

- 使用者可以輸入：
  - 初始投資金額
  - 每年定期投入金額
  - 預期報酬率（％）
  - 投資年數
- 自動計算每年的累積報酬
- 顯示年度報表結果
- 即時更新結果
- 基礎表單驗證（避免空值或 0）


