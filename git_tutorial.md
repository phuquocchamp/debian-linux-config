### GIT COMMON COMMAND BY PHUQUOCCHAMP

#### git init

##### 1. git init

Lệnh `git init` được sử dụng để khởi tạo một kho lưu trữ Git trong thư mục làm việc hiện tại. Khi bạn chạy lệnh này, Git tạo ra một thư mục `.git` ẩn trong thư mục làm việc. Thư mục `.git` này chứa toàn bộ lịch sử commit, các thông tin về nhánh, tag, và các cài đặt khác của kho lưu trữ Git.

Cú pháp:

```bash
git init
```

Khi đã chạy lệnh này, bạn có thể thêm tệp tin và thực hiện các commit trong thư mục làm việc của bạn.

##### 2. git init --bare

Ngược lại, lựa chọn `--bare` khi sử dụng `git init` tạo ra một kho lưu trữ Git không có thư mục làm việc làm trung gian. Kho lưu trữ "bare" chỉ chứa dữ liệu Git mà không có bất kỳ bản sao làm việc hoặc thư mục làm việc cụ thể. Kho lưu trữ "bare" thường được sử dụng khi bạn muốn tạo ra một kho lưu trữ tập trung mà nhiều người có thể chia sẻ.

Cú pháp:

```bash
git init --bare <name_repo>
```

Kho lưu trữ "bare" thường được sử dụng trên máy chủ từ xa, nơi mà mọi người có thể đẩy (push) và kéo (pull) từ đó mà không làm việc trực tiếp trong thư mục `.git`. Kho lưu trữ "bare" không có một thư mục làm việc để chứa các tệp làm việc thông thường, và nó chỉ chứa các đối tượng Git, refs và các thông tin liên quan đến lịch sử commit.

#### git status

Lệnh git status dùng để kiểm tra trạng thái của các file, thư mục trong working area và staging area

```bash
git status
```

#### git add

Thêm thay đổi từ working area sang staging area

Thêm một tập tin cụ thể.

```bash
git add [file]
```

Thêm tất cả thay đổi trong working area.

```bash
git add .
```
