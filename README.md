# MeowPlanet

專案網址：

https://meowplanet.lol/Missings (部屬至Azure)

負責專案中「地圖協尋(Google Maps API)」、「即時聊天(ASP.NET Core SignalR)」資料庫設計及網頁全端開發。

使用技術：

程式語言－HTML/CSS/Javascript, C#

前端框架－jQuery, Bootstrap

Web框架－ASP.NET Core MVC(.NET 6)

資料庫存取－MSSQL, Entity Framework Core, LINQ

版本控制－Git

－功能介紹－

過濾資訊：

依地圖中心點過濾出附近走失貓咪，減少網頁載入資源。

![介紹](https://user-images.githubusercontent.com/103472129/183888915-261614de-2bec-4a56-a58e-98b17739f305.gif)


刊登協尋：

透過地圖插點的方式描述走失的位置，再選擇已登記的貓咪進行刊登。

（註：目前設計一位會員只能有一筆刊登；若須取消請至右上角會員 > 協尋管理 > 已尋回）

![刊登3](https://user-images.githubusercontent.com/103472129/183888066-b816bc78-de34-4c7e-932a-c3db6912f4f4.gif)


提供線索：

若有人目擊到身形相似的貓咪可對該筆協尋提供線索，發揮群眾的力量提高尋獲率。

（註：提供後須等待飼主同意，即可顯示於地圖上）

![線索刊登](https://user-images.githubusercontent.com/103472129/183889713-8f9353c2-928e-45e3-b86d-e64520b24082.gif)


查看線索：

每筆協尋都有各自的線索，點擊後會出現該貓咪出現過的地點及路徑

（註：只會顯示出所有「經飼主認可」的線索資訊，防止有心人濫用此系統）

![線索](https://user-images.githubusercontent.com/103472129/183890359-7308aac5-fd09-45db-b897-907682d4f236.gif)


會員 > 協尋管理：

管理他人提供的線索，可選擇釘選（顯示於地圖上）或移除（不顯示於地圖上）

即時通訊：

具有歷史訊息、時間戳記、傳送圖片、未讀提醒等功能的即時通訊系統

![訊息](https://user-images.githubusercontent.com/103472129/183891579-49efc521-4332-4170-aae4-9c26a99f3d7f.gif)

