# 增進網頁路由

## 簡介

我們的網頁路由的定義只包含模板的 ID。但當顯示新的網頁頁面時，我們或許會用到更多東西。讓我們來增進我們的網頁路由方式，新增兩項功能：

- 給各個模板標題，在模板切換後同時更新網頁視窗的標題。
- 加入額外選項，在模板切換後執行特定程式。我們希望在切換到儀表板頁面時，在開發者命令欄顯示 `'Dashboard is shown'`。 

## 學習評量

| 作業內容 | 優良                                                     | 普通                                                                                          | 待改進                   |
| -------- | -------------------------------------------------------- | --------------------------------------------------------------------------------------------- | ------------------------ |
|          | 兩個新功能運作正常，標題與程式也能執行新的 `routes` 規則 | 兩個新功能運作正常，但行為是 hardcoded 上去而非使用 `routes` 規則。新的路由規則無法完整地運作 | 新功能不完全或不正常運行 |
