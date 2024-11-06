# Hướng dẫn triển khai đầy đủ
(link full by crazypeace) https://zelikk.blogspot.com/2022/07/url-shorten-worker-hide-tutorial.html

// ntannn đang update, nma nhác quas :))

# Nếu không muốn bị ảnh hưởng bởi các cập nhật của tác giả
- Fork một bản repo của riêng bạn.

- Trong file `worker.js` của Cloudflare, tìm kiếm `"https://ntanthedev.github.io/Url-Shorten-Worker/" + config.theme + "/index.html"`, thay thế `ntanthedev` bằng tên của bạn, như vậy worker của Cloudflare sẽ lấy file `index.html` từ repo của bạn.
  ![image](https://github.com/ntanthedev/Url-Shorten-Worker/assets/665889/c98ca134-2809-4490-b9f7-ac27ba735e2e)

- Trong repo mà bạn đã fork, chỉnh sửa file `index.html`, tìm kiếm `"https://ntanthedev.github.io/Url-Shorten-Worker/main.js"`, thay thế `ntanthedev` bằng tên của bạn, như vậy file `index.html` sẽ lấy file `main.js` từ repo của bạn.
  ![image](https://github.com/ntanthedev/Url-Shorten-Worker/assets/665889/5f283aa2-d57f-4679-a987-757f1590e8f9)

- Kích hoạt tính năng GitHub Pages cho repo của bạn. (Vui lòng tìm kiếm trên Google để biết chi tiết, không giải thích cụ thể ở đây)

# Hướng dẫn sửa đổi dựa trên phiên bản gốc (by crazypeace)
Trả về 404 khi truy cập trực tiếp tên miền. Thiết lập một entry trong KV để lưu đường dẫn bí mật, chỉ hiển thị trang sử dụng khi truy cập đường dẫn này.  
https://zelikk.blogspot.com/2022/07/url-shorten-worker-hide-tutorial.html

Hỗ trợ tùy chỉnh đường dẫn ngắn  
https://zelikk.blogspot.com/2022/07/url-shorten-worker-custom.html

API không cung cấp công khai  
https://zelikk.blogspot.com/2022/07/url-shorten-worker-api-password.html

Trang web lưu cache các đường dẫn ngắn đã thiết lập  
https://zelikk.blogspot.com/2022/08/url-shorten-worker-localstorage.html

Tìm kiếm trước trong localStorage cho ô nhập liệu đường dẫn dài  
https://zelikk.blogspot.com/2022/08/url-shorten-worker-bootstrap-list-group-oninput.html

Thêm nút xóa đường dẫn ngắn  
https://zelikk.blogspot.com/2022/08/url-shorten-worker-delete-kv-localstorage.html

Tính năng đếm lượt truy cập, có thể truy vấn đường dẫn ngắn, trở thành hệ thống API rút gọn URL hoàn chỉnh  
https://zelikk.blogspot.com/2023/11/url-shorten-worker-visit-count-api-api.html

Tính năng tự hủy sau khi đọc, có thể tạo mã QR dùng một lần  
https://zelikk.blogspot.com/2023/11/url-shorten-worker-snapchat-mode.html

Thêm tính năng đọc tất cả các bản ghi trong KV  
https://zelikk.blogspot.com/2024/01/url-shorten-worker-load-cloudflare-kv.html

Biến thành Pastebin  
https://zelikk.blogspot.com/2024/01/url-shorten-worker-pastebin.html

Bảo vệ key 'password'  
https://zelikk.blogspot.com/2024/01/url-shorten-worker-password-protect-keylist.html

Biến thành trang lưu trữ hình ảnh  
https://zelikk.blogspot.com/2024/01/url-shorten-worker-image-hosting-base64.html

Biến thành nhật ký mạng hỗ trợ Markdown  
https://zelikk.blogspot.com/2024/02/url-shorten-worker-netjournal.html  
https://zelikk.blogspot.com/2024/02/url-shorten-worker-netjournal-markdown.html  
https://zelikk.blogspot.com/2024/04/url-shorten-worker-netjournal-markdown.html

# Hãy cho tôi biết repo này hữu ích với bạn bằng cách tặng sao! Chào mừng các ngôi sao! :)
[![Stargazers over time](https://starchart.cc/ntanthedev/Url-Shorten-Worker.svg)](https://starchart.cc/ntanthedev/Url-Shorten-Worker)
