# AppleTree-backend
Tags: README
<br><br>


## 簡述
1、「Apple Tree 3C電商網站」是我們團隊所製作的專案，此購物網站主要販售蘋果系列3C產品。

2、在這個repository中主要內容是此電商網站的『**後端**』程式(前台+後台)。

3、此專案為前後端分離的架構，前端程式使用的工具為Vue.js，主要負責頁面的呈現。後端程式使用的工具則為Spring Boot，主要負責邏輯處理，並從資料庫中進行資料的存取。
<br><br>


## 專案功能
1、主頁面：功能導覽、註冊/登入、聯絡資訊。

2、一般使用者介面：
      (1)會員中心：修改個人資料、查看交易紀錄、意見反饋。
      (2)商城瀏覽：產品追蹤、加入購物車、結帳。

3、後台管理者介面：
      使用者管理、產品管理、訂單管理、數據分析、意見反饋處理。
<br><br>


## 運行環境需求
- 前端（Frontend）：Vue.js
- 後端（Backend）：Spring Boot、MSSQL
<br><br>


## 在Local端的運行步驟
1、開啟IntelliJ，依序點選File→New→Project from Version Control。

2、在URL欄位貼上：[https://github.com/ShengRuYang/AppleTree-backend.git](https://github.com/ShengRuYang/AppleTree-backend.git)。
      即可將此repository的內容(電商網站的『後端』程式)clone到Local端。

3、在IntelliJ中點選「Run 'MalltestApplication'」，即可運行此專案的『後端』程式。
<br><br>


## 資料夾說明
- config - 用於配置第三方認證的相關設定。
- controller - 放置各功能的controller。
- dto - 放置各DTO，做為資料傳輸的載體。
- model - 各Entity的放置處。
- repository - 各repository的放置處。
- service - 放置各功能的service。
<br><br>
