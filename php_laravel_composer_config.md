# INSTALL COMPOSER ON LINUX 
Để cài đặt Composer trên MX Linux (hoặc bất kỳ hệ điều hành Linux nào), bạn có thể thực hiện các bước sau:

1. **Cài đặt Dependencies**: Trước tiên, hãy chắc chắn rằng bạn đã cài đặt PHP và các phần mềm cần thiết cho Composer. Dùng trình quản lý gói của hệ điều hành, bạn có thể cài đặt PHP và các phần mềm khác. Trong MX Linux, bạn có thể sử dụng APT:

   ```
   sudo apt update
   sudo apt install php php-cli php-zip php-mbstring
   ```

2. **Tải Composer**: Sử dụng cURL để tải Composer và lưu nó vào thư mục `/usr/local/bin`. Composer là một công cụ toàn hệ thống, nên bạn cần quyền root (sudo) để thực hiện điều này:

   ```
   sudo curl -sS https://getcomposer.org/installer | sudo php -- --install-dir=/usr/local/bin --filename=composer
   ```

3. **Kiểm tra cài đặt**: Đảm bảo rằng Composer đã được cài đặt đúng bằng cách chạy lệnh:

   ```
   composer --version
   ```

   Bạn nên thấy phiên bản của Composer hiện ra.

Bây giờ bạn đã cài đặt Composer thành công trên MX Linux. Bạn có thể sử dụng Composer để quản lý các thư viện và gói PHP trong dự án của mình.