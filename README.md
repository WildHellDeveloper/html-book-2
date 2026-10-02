# Tôi Tài Giỏi, Bạn Cũng Thế! – Landing page giới thiệu sách

Trang giới thiệu (single page, HTML tĩnh) cuốn sách **“Tôi Tài Giỏi, Bạn Cũng Thế!”** của Adam Khoo.

## Cấu trúc

```
index.html          ← toàn bộ HTML + CSS + JS
assets/book/        ← ảnh bìa sách (dùng file .jpg)
assets/fonts/       ← font tự host (có tiếng Việt), chạy được cả khi offline
assets/author.jpg   ← (tuỳ chọn) ảnh tác giả – thêm vào là tự hiện
```

## Đưa lên GitHub Pages

1. Push toàn bộ thư mục lên một repo GitHub.
2. Vào **Settings → Pages → Build and deployment**, chọn *Deploy from a branch*, branch `main`, thư mục `/ (root)`.
3. Sau khoảng 1 phút, trang có tại `https://<tên-user>.github.io/<tên-repo>/`.

## Chế độ thuyết trình

- Nhấn **P** (hoặc nút “Thuyết trình” góc phải dưới) để bật/tắt.
- **→ / ↓ / Space**: phần tiếp · **← / ↑**: phần trước · **Home / End**: đầu / cuối
- **F**: toàn màn hình · **Esc**: thoát

## Tuỳ chỉnh nhanh

- **Ảnh tác giả:** đặt file `assets/author.jpg` (tỉ lệ 4:5). Khi chưa có ảnh, khung polaroid hiện chữ “AK”.
- **Màu sắc:** sửa các biến trong `:root` ở đầu thẻ `<style>` (`--blue`, `--yellow`, `--cream`…).
- **Ảnh bìa:** nếu đổi ảnh, sửa đường dẫn trong `.book .front` (CSS) và thẻ `og:image`.

## Nguồn thông tin tác giả

- Wikipedia – Adam Khoo: https://en.wikipedia.org/wiki/Adam_Khoo
- AKLTG – Adam Khoo: https://www.akltg.com/leaders/adam-khoo/
