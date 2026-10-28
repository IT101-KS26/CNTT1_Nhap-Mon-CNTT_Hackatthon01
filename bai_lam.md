# BÀI LÀM – HACKATHON 01

- **Mã đề:** 15
- **Họ tên:** Dương Công Quốc
- **Lớp:** CNTT1
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** Windowns

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
pwd
get-childitem 
mv bang_gia_goi.txt docs
mv .\Logo_Studio_Anh.PNG media

rm *.tmp

```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
PS D:\Studio-anh-website> pwd

Path
----
D:\Studio-anh-website


PS D:\Studio-anh-website> Get-childitem


    Directory: D:\Studio-anh-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   8:08 AM                backup
d-----        10/28/2026   8:09 AM                data
d-----        10/28/2026   8:08 AM                docs
d-----        10/28/2026   8:10 AM                logs
d-----        10/28/2026   8:08 AM                media
------        10/27/2026   1:32 AM             71 .env
-a----        10/28/2026   8:11 AM           2259 bai_lam.md
------        10/27/2026   1:32 AM             59 Bang Gia Goi.txt
------        10/27/2026   1:32 AM           7231 Logo Studio
                                                  Anh.PNG
------        10/27/2026   1:32 AM             22 temp_238.tmp


PS D:\Studio-anh-website> mv bang_gia_goi.txt docs
PS D:\Studio-anh-website> mv .\Logo_Studio_Anh.PNG media
PS D:\Studio-anh-website> cd media
PS D:\Studio-anh-website\media> cp .\Logo_Studio_Anh.PNG backup
PS D:\Studio-anh-website\media> cd ..
PS D:\Studio-anh-website> rm *.tmpPS D:\Studio-anh-website> pwd

Path
----
D:\Studio-anh-website


PS D:\Studio-anh-website> Get-childitem


    Directory: D:\Studio-anh-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   8:08 AM                backup
d-----        10/28/2026   8:09 AM                data
d-----        10/28/2026   8:08 AM                docs
d-----        10/28/2026   8:10 AM                logs
d-----        10/28/2026   8:08 AM                media
------        10/27/2026   1:32 AM             71 .env
-a----        10/28/2026   8:11 AM           2259 bai_lam.md
------        10/27/2026   1:32 AM             59 Bang Gia Goi.txt
------        10/27/2026   1:32 AM           7231 Logo Studio
                                                  Anh.PNG
------        10/27/2026   1:32 AM             22 temp_238.tmp


PS D:\Studio-anh-website> mv bang_gia_goi.txt docs
PS D:\Studio-anh-website> mv .\Logo_Studio_Anh.PNG media
PS D:\Studio-anh-website> cd media
PS D:\Studio-anh-website> rm *.tmp

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/lich_chup_thang_5.xlsx`, không cần ghi vào đây.
