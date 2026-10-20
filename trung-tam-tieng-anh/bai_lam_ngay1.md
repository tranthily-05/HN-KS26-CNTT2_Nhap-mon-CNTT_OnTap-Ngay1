# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên:** Trần Thị Lý
- **Lớp:** HN-KS26-CNTT2
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** Windows 

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
# B1: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh> pwd
# B2: C:\Users\fpt yen thanh\Downloads>trung-tam-tieng-anh> Get-ChildItem -Forse
# B3: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh> mv .\lich_hoc.txt .\docs\
# C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh> mv .\anh_lop_hoc.jpg, .\logo_trung_tam.png .\media\
# B4: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh> cd .\media\
# C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh> cp .\media\logo_trung_tam.png .\archive\
# B5: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh> rm .\temp_201.tmp
# C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh> rm .\temp_202.tmp
# B6: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh> cd logs
# C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh\logs> ls
# B7: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh\logs> cd ..
# C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh> cd docs
# C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh\docs> cp ..\media\anh_lop_hoc.jpg ..\archive
# C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh\docs> cd ..
```

### Kết quả B1 (pwd)

```text
C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh

```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
  Directory: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/20/2026   9:11 PM                archive
d-----        10/20/2026   8:33 PM                data
d-----        10/20/2026   8:56 PM                docs
d-----        10/20/2026   8:32 PM                logs
d-----        10/20/2026   8:57 PM                media
d-----        10/20/2026   8:46 PM                Trung Tam Tieng Anh FINAL
-a----        10/20/2026   7:47 PM             83 .env
-a----        10/20/2026   7:47 PM            902 bai_lam_ngay1 - Copy.md
-a----        10/20/2026   7:47 PM            902 bai_lam_ngay1.md


    Directory: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh\archive


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   7:47 PM          13559 anh_lop_hoc.jpg
-a----        10/20/2026   7:47 PM           5184 logo_trung_tam.png


    Directory: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh\data


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   7:47 PM           5070 hoc_vien_khoa_3.xlsx


    Directory: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh\docs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   7:47 PM             67 lich_hoc.txt


    Directory: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh\logs


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   7:47 PM           1072 access.log


    Directory: C:\Users\fpt yen thanh\Downloads\trung-tam-tieng-anh\media


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        10/20/2026   7:47 PM          13559 anh_lop_hoc.jpg
-a----        10/20/2026   7:47 PM           5184 logo_trung_tam.png

```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** ..../100
- **Lỗi mình đã mắc và cách sửa:**
