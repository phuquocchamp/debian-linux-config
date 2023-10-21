# Install Postman on MX - Linux

1. **Tải Postman:**
   - Truy cập trang web chính thức của Postman tại: https://www.postman.com/downloads/
   - Tải phiên bản Postman dành cho Linux bằng định dạng tệp tin .tar.gz.

2. **Giải nén Postman:**
   - Mở terminal và di chuyển đến thư mục chứa tệp tin Postman bạn vừa tải xuống.
   - Sử dụng lệnh sau để giải nén tệp tin .tar.gz:
     ```
     tar -xzf Postman-Linux-x64-<version>.tar.gz
     ```

3. **Di chuyển Postman vào thư mục /opt:**
   - Sử dụng lệnh sau để di chuyển thư mục Postman vào thư mục `/opt` (cần quyền quản trị):
     ```
     sudo mv Postman /opt
     ```

4. **Tạo liên kết tượng trưng:**
   - Để có thể chạy Postman từ bất kỳ nơi nào trong hệ thống, bạn có thể tạo liên kết tượng trưng (symlink) đến thực thi Postman trong thư mục `/opt`.
     ```
     sudo ln -s /opt/Postman/Postman /usr/local/bin/postman
     ```

5. **Tạo Menu Trình ứng dụng (tuỳ chọn):**
   - Để thêm Postman vào trình ứng dụng của bạn, bạn có thể tạo một tệp `.desktop`. Ví dụ:
     ```
     sudo nano /usr/share/applications/postman.desktop
     ```
     Và sau đó thêm nội dung sau vào tệp `.desktop`:
     ```
     [Desktop Entry]
     Encoding=UTF-8
     Name=Postman
     Exec=postman
     Icon=/opt/Postman/app/resources/app/assets/icon.png
     Terminal=false
     Type=Application
     Categories=Development;
     ```

6. **Khởi chạy Postman:**
   - Bây giờ bạn có thể khởi chạy Postman bằng cách gõ `postman` trong terminal hoặc tìm kiếm nó trong trình ứng dụng.

