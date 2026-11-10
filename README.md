# 搭檔圖鑑｜AI 協作性格測驗

12 道生活選擇題，找出你是 16 種搭檔裡的哪一種，帶走一張寫給你的 AI 指令卡。

**線上版：<https://g23988.github.io/partner-dex/>**

- 結果頁有個性描述、指揮 AI 的強項和容易踩的坑、一段可以直接貼給 AI 的專屬指令。
- 可以存成圖片、列印 A4、用 QR 碼把結果帶到手機。
- 純靜態網頁，沒有後端。作答只留在瀏覽器；結果連結裡只有 12 題的選擇。

題目借用 MBTI 四組偏好設計，每組三題。16 型的描述是原創內容，沒有經過心理計量驗證，結果只代表這次作答的傾向。

## 檔案

- `index.html`：整個測驗（題目、16 型內容、樣式、程式）。
- `qrcode.js`：[qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) 1.4.4，Kazuhiko Arase，MIT 授權。

## 本機預覽

直接用瀏覽器打開 `index.html`。本機開檔時，存下來的圖片不會有 QR 碼。
