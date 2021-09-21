# Bài tập 1 - Thống kê keyword của tiêu đề trong một hội nghị
Opened: Thứ sáu, 10 Tháng chín 2021, 12:00 AM
Due: Thứ sáu, 17 Tháng chín 2021, 11:55 PM
## Các bước:
Bước 0: (khuyến khích) Crawl tên bài báo trong một đường link

Dùng tay copy tên bài báo bỏ vào file rồi lọc lại tên bài báo chứ ko có tác giả hoặc loại file.

Bước 1: Đọc tất cả tên bài báo của một hội nghị trong năm 2021 (~1 dòng code)

Bước 2: Tách từ bằng dấu khoảng trắng và viết thường hết toàn bộ ký tự (tolower) (~1 dòng code)

Bước 3: Loại bỏ stopword

Bước 4:  thống kê số lần xuất hiện theo từng keyword (~ 2 dòng code)

Bước 5: Vẽ biểu đồ các keyword theo thứ tự giảm dần số lần xuất hiện (~5 dòng code). Dùng matplotlib.pyplot.

Danh sách hội nghị: 

0. CVPR2021

1. WACV 2021

2. CVPR 2020

3. WACV 2020

4. SIGGRAPH 2021 (https://kesen.realtimerendering.com)

5. ICCV 2019

6. NIPS 2020 (https://papers.nips.cc/paper/2020)

Lưu ý: Mỗi sinh viên sẽ chọn topic theo quy tắc sau: MSSV mode 7. Ví dụ: MSSV = 1812345 thì sẽ vẽ biểu đồ thống kê cho topic  3 WACV2020  (vì 1812345 mod7 = 3)

Nộp file mã nguồn và ảnh kết quả. Không nộp link Colab.