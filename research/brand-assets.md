# Nhận diện và ảnh – 16/10/2026

Logo nguồn do chủ website cung cấp, lưu tại public/assets/logo-original.jpg.
Bản tách nền PNG/WebP dùng cho đầu trang, chân trang, biểu trưng trang chủ và favicon; bản JPG dùng cho chia sẻ liên kết.
Bảng màu: xanh #263f32; vàng đồng #987329; hồng sen #b76f73; nền kem #faf6ed.

Ảnh phòng và tiếp khách: bản xử lý bằng công cụ imagegen tích hợp, cân chỉnh ánh sáng, giảm nhiễu, bảo toàn bố cục. Bản gốc vẫn được lưu và liên kết ở trang nguồn. Ảnh AI có thể thay đổi chi tiết nhỏ, không dùng làm hồ sơ kỹ thuật.

Prompt logo: Remove white background to transparency, preserve circular emblem, gold ornamental rings, hand, muscle, lotus, herbs and exact Vietnamese text Y HỌC CỔ TRUYỀN / GIẢI CƠ SÂU; clean JPEG noise.
Prompt ảnh: Conservatively improve exposure and white balance, reduce JPEG noise, preserve room layout, furniture, objects and camera watermark; no new objects.

apply_brand.py chạy sau refresh_site.py trong build_content.py để duy trì nhận diện khi dựng lại nội dung.
