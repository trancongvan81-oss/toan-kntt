# Mỗi ngày một bài Toán – KNTT

Thư viện thí nghiệm tương tác Toán THPT theo Chương trình GDPT 2018, sách
Kết nối tri thức với cuộc sống. Chuyên mục “Mỗi ngày một bài Toán – Một điều
đáng suy ngẫm”: mỗi bài đăng Facebook dẫn đến một thí nghiệm tại đây — học
sinh kéo thanh trượt, thử nghiệm và khám phá.

Trang chủ: https://trancongvan81-oss.github.io/toan-kntt/

## Cấu trúc

```
index.html                        Trang chủ: đủ cả 3 khối 10 / 11 / 12
10/                               Thí nghiệm Toán 10
  do-khoang-cach/
    index.html                    Bài 04 — Đo khoảng cách mà không cần đến đích (Toán 10)
                                  AB = 60 m, góc A = 60°, góc B = 45°, AC ≈ 43,9 m.
                                  Định lí sin. Đo khoảng cách gián tiếp.
11/                               Thí nghiệm Toán 11
  can-cau-quay/
    index.html                    Bài 05 — Cần cẩu quay, điều gì không đổi? (Toán 11)
                                  Cần AB = 12 m, nằm ngang ở độ cao 8 m.
                                  AB ∥ (P) ở mọi hướng quay; hạ xuống 0 m thì AB ⊂ (P).
12/
  hop/
    index.html                    Bài 03 — Chiếc hộp không nắp (Toán 12)
                                  Tấm bìa vuông 24 cm, cắt tối ưu x = 4 cm,
                                  Vmax = 1.024 cm³. Ứng dụng đạo hàm.
```

Mỗi thí nghiệm là một file HTML độc lập: không cần Internet sau khi tải về,
không cần đăng nhập, không thu thập dữ liệu.

## Thêm một bài mới

1. Tạo thư mục `<khối>/<tên-bài>/` và đặt `index.html` vào đó.
2. Thêm một mục vào đúng khối trong `index.html` ở thư mục gốc, trỏ tới
   thư mục bài mới.
3. Đăng bài Facebook kèm liên kết tới thư mục bài mới.

## Đăng web (GitHub Pages)

Repo công khai. Vào **Settings → Pages → Build and deployment → Deploy from
a branch**, chọn nhánh `main`, thư mục `/ (root)`, rồi **Save**. Liên kết
trang sẽ có dạng `https://trancongvan81-oss.github.io/toan-kntt/`,
mỗi bài thêm đường dẫn thư mục của nó, ví dụ:

`https://trancongvan81-oss.github.io/toan-kntt/12/hop/`
