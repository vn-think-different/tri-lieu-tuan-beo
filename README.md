# Massage trị liệu Tuấn Béo

Website tiếng Việt, HTML/CSS/JS tĩnh, tối ưu khả năng đọc trên điện thoại và nhóm người trưởng thành, trung niên. Bảng màu xanh trầm/ngà/vàng đất; hỗ trợ bàn phím và reduced motion.

## Chạy cục bộ
`python3 -m http.server 8000 --directory public`

## Vercel
Import repository `vn-think-different/tri-lieu-tuan-beo`, chọn preset Other, output directory `public`, không cần build command. Cấu hình trong vercel.json. Chưa có deployment được xác nhận; phải kết nối tài khoản Vercel trước khi triển khai qua tích hợp.
Nguồn: https://vercel.com/docs/git và https://vercel.com/docs/deployments/overview

## Nội dung
- public/index.html: trang thương hiệu, kiến thức, công cụ dự kiến, địa chỉ.
- public/*html: ba bài kiến thức, trang nguồn, 404.
- research/: báo cáo xác minh, dữ liệu vị trí gốc, kế hoạch bổ sung.
- build_content.py: tạo lại trang và cấu hình; chỉnh dữ liệu trong script để giữ nhất quán.
- public/assets/: ảnh người dùng cung cấp và minh họa SVG tự tạo.

Không có đơn hàng/đặt lịch/thanh toán giả, số điện thoại giả, lời chứng thực hoặc chứng chỉ tự tạo. Danh mục chưa mở bán. Không sử dụng ảnh vệ tinh để suy ra quy mô hoạt động hoặc quyền sở hữu.

## Cần bổ sung
Logo gốc, ảnh cơ sở/dịch vụ có quyền sử dụng, điện thoại/Zalo, giờ mở cửa, người phụ trách và hồ sơ chuyên môn, dịch vụ/giá, sản phẩm/SKU/giá/tồn kho, giao hàng/đổi trả, chính sách dữ liệu, tên miền. Chỉ mở checkout sau khi có backend và thông tin bán hàng thực tế.
