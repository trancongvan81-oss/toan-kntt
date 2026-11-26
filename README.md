# Mỗi ngày một bài Toán – KNTT

Thư viện thí nghiệm tương tác Toán THPT theo Chương trình GDPT 2018, sách
Kết nối tri thức với cuộc sống. Chuyên mục “Mỗi ngày một bài Toán – Một điều
đáng suy ngẫm”: mỗi bài đăng Facebook dẫn đến một thí nghiệm tại đây — học
sinh kéo thanh trượt, thử nghiệm và khám phá.

Trang chủ: https://trancongvan81-oss.github.io/moi-ngay-mot-bai-toan-kntt/

## Cấu trúc

```
index.html                        Trang chủ: đủ cả 3 khối 10 / 11 / 12
lop-10/                           Thí nghiệm Toán 10 (đang cập nhật)
lop-11/                           Thí nghiệm Toán 11 (đang cập nhật)
lop-12/
  bai-03-hop-khong-nap/
    index.html                    Bài 03 — Chiếc hộp không nắp (Toán 12)
                                  Tấm bìa vuông 24 cm, cắt tối ưu x = 4 cm,
                                  Vmax = 1.024 cm³. Ứng dụng đạo hàm.
```

Mỗi thí nghiệm là một file HTML độc lập: không cần Internet sau khi tải về,
không cần đăng nhập, không thu thập dữ liệu.

## Thêm một bài mới

1. Tạo thư mục `lop-<khối>/bai-<số>-<tên-bài>/` và đặt `index.html` vào đó.
2. Thêm một mục vào đúng khối trong `index.html` ở thư mục gốc, trỏ tới
   thư mục bài mới.
3. Đăng bài Facebook kèm liên kết tới thư mục bài mới.

## Đăng web (GitHub Pages)

Repo công khai. Vào **Settings → Pages → Build and deployment → Deploy from
a branch**, chọn nhánh `main`, thư mục `/ (root)`, rồi **Save**. Liên kết
trang sẽ có dạng `https://trancongvan81-oss.github.io/moi-ngay-mot-bai-toan-kntt/`,
mỗi bài thêm đường dẫn thư mục của nó, ví dụ:

`https://trancongvan81-oss.github.io/moi-ngay-mot-bai-toan-kntt/lop-12/bai-03-hop-khong-nap/`
