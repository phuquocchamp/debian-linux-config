# Install Jetbrain Toolbox On Linux

Để cài đặt JetBrains Toolbox App trên Linux, bạn có thể tuân theo các bước sau:

1. **Tải Toolbox App:**

   - Trước tiên, bạn cần tải tệp tarball .tar.gz của JetBrains Toolbox App từ trang web của Toolbox App.
2. **Giải nén tarball:**

   - Sau khi tải xong, bạn cần giải nén tarball này vào một thư mục hỗ trợ thực thi tệp tin.
   - Ví dụ, nếu phiên bản bạn đã tải là 1.17.7391, bạn có thể giải nén nó vào thư mục /opt, được đề xuất, bằng lệnh sau:
     ```
     sudo tar -xzf jetbrains-toolbox-1.17.7391.tar.gz -C /opt
     ```
   - Đổi tên cho folder để tiện sử dụng:

     ```bash 
     sudo rm /opt/jetbrains-toolbox-1.17.7391 /opt/jetbrains-toolbox
     ```
3. **Chạy Toolbox App:**

   - Sau khi bạn đã giải nén, bạn có thể chạy tệp thực thi `jetbrains-toolbox` từ thư mục bạn đã giải nén để chạy Toolbox App.
   - Ví dụ:
     ```
     /opt/jetbrains-toolbox/jetbrains-toolbox
     ```
4. **Thêm biểu tượng Toolbox App vào menu chính:**

   - Sau khi chạy Toolbox App lần đầu tiên, nó sẽ tự động thêm biểu tượng Toolbox App vào menu chính của bạn.
