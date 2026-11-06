# Gia sư Nhật Trung — trang trưng bày Cấp 6

Trang tĩnh công khai giới thiệu chức năng, quy trình, tiêu chuẩn kiểm tra và giới hạn của Agent Gia sư Nhật Trung.

## Riêng tư và an toàn

- Nội dung trong `site/` được tải lên GitHub Pages, gồm cả trang trưng bày và workbench cá nhân.
- Trang là bản mô phỏng có ghi rõ; người xem không thể gửi yêu cầu cho Agent.
- Repo này không chứa Hermes profile, `SOUL.md`, log, khóa/API token, tệp học cá nhân hoặc thông tin xác thực Lark.
- Đây là repo công khai nếu xuất bản bằng GitHub Free. Hãy kiểm tra nội dung trước khi xác nhận công khai.

## Xuất bản

Workflow trong `.github/workflows/pages.yml` triển khai `site/` lên GitHub Pages khi có push lên nhánh `main` hoặc chạy thủ công từ Actions. Trong repo GitHub, đặt **Settings → Pages → Build and deployment → Source: GitHub Actions**.

## Chạy xem trước trên Windows

Mở `site/index.html` bằng trình duyệt. Không cần cài đặt máy chủ hay cung cấp khóa API.

## Workbench công khai

Trang cá nhân tĩnh được xuất tại site/workbench/. Đây là trang công khai; mỗi người xem có dữ liệu localStorage riêng trong trình duyệt của họ. Không có API, Lark/Hermes hay khóa truy cập.

