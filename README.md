# Website Toán học 10–12 (bản mẫu miễn phí)

Website tĩnh dùng HTML, CSS, JavaScript và JSON, có thể triển khai miễn phí trên GitHub Pages với repository công khai.

## Chạy thử
Mở `index.html` trong trình duyệt. Do trình duyệt có thể chặn `fetch()` từ tệp cục bộ, nên tốt nhất chạy bằng một local web server hoặc triển khai lên GitHub Pages.

## Chỉnh sửa thương hiệu
Mở `data/content.json`, sửa các trường `brand.siteName`, `brand.teacherName`, `brand.slogan` và `brand.copyright`.

## Thêm chương
Trong `data/content.json`, tìm mảng `grades`, chọn khối lớp rồi thêm mục vào `chapters`. Nội dung hiện tại chỉ là dữ liệu minh họa, cần được giáo viên xác nhận trước khi sử dụng chính thức.

## Triển khai miễn phí bằng GitHub Pages
1. Tạo repository mới trên GitHub và đặt chế độ Public.
2. Tải lên toàn bộ nội dung thư mục này, bảo đảm `index.html` nằm ở thư mục gốc repository.
3. Vào **Settings → Pages**.
4. Chọn **Deploy from a branch**, branch `main`, folder `/(root)`, rồi lưu.
5. Chờ GitHub Pages xuất bản website và mở đường dẫn được cung cấp trong phần Pages.

Hướng dẫn chính thức: https://docs.github.com/en/pages/getting-started-with-github-pages

## Giới hạn hiện tại
- Đây là bản giao diện mẫu tương tác: chọn khối lớp, mở chương và xem lịch sử cục bộ.
- Hệ thống làm đề, bộ chấm điểm, đồng hồ thi, lời giải chính thức, tài khoản học sinh và đồng bộ Google Sheets chưa được tích hợp trong bản mẫu này.
- Lịch sử hiện tại dùng `localStorage`; không đồng bộ giữa thiết bị.
- MathJax được tải từ CDN nên cần kết nối internet để hiển thị công thức nâng cao.
- Không nhập dữ liệu cá nhân nhạy cảm. Không có backend hoặc cơ sở dữ liệu dùng chung.
