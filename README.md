Tool cập nhật LeagueAI.
=====


Cách sử dụng
===
- Tải về và giải nén tệp tin "UpdateBotAI.zip" ở cùng folder **đã giải nén** của game LeagueAI.exe.
- Sau khi giải nén xong thì chỉ cần chạy "UpdateBotAI.exe" là nó sẽ tự cập nhật.
- Cấu trúc file cập nhật được sẽ trông thế này:
```
D:.
└───Đây là thư mục đã giải nén của game LeagueAI
        config.json
        LeagueAI.exe            <====================== Đây chính là bot.
        InputManager.dll
        Leaf.xNet.dll
        Newtonsoft.Json.dll
        UpdateBotAI.exe         <====================== Đây là tệp tin mới trong gói "UpdateBotAI.zip"
        HtmlAgilityPack.dll     <====================== Đây cũng là tệp tin mới trong gói "UpdateBotAI.zip"
```


Giải thích cách hoạt động
===
- Công cụ này hoạt động bằng cách kiểm tra mã hash md5 của phần mềm hiện tại và trên kho lưu trữ.
- Nếu thấy thay đổi, nó sẽ tự cập nhật.
