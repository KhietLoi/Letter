# Tự tạo link mời

Mở https://khietloi.github.io/Letter/, chọn **Tạo link mời**, điền tên bất kỳ và nhấn **Sao chép link**.

Ví dụ: https://khietloi.github.io/Letter/#Tiểu-Băng

Tên nằm ngay trong link, thiệp tự đọc và hiển thị **Tiểu Băng** với đầy đủ dấu. Không cần tạo trang, lưu danh sách tên hay cập nhật GitHub mỗi lần mời người mới. Trình duyệt hoặc ứng dụng nhắn tin có thể mã hóa chữ có dấu trong URL; tên trên thiệp vẫn đúng.

Các link cũ dạng `test.html?name=...` (hoặc `ten`, `to`) tiếp tục hoạt động. Cả trang chính và `test.html` đều mở thiệp trực tiếp, tránh chuyển hướng qua lại khi trình duyệt giữ bản cũ.

Giao diện và chức năng nằm trong `index.html`; `test.html` là bản sao để hỗ trợ địa chỉ cũ. Sau khi sửa giao diện, đồng bộ hai file này. Khi tải lên hosting, giữ `index.html`, `test.html`, `.nojekyll` và thư mục `assets/`.
