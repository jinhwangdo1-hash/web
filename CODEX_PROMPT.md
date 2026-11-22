# Codex: Thiên Đạo AI Game Studio

Bạn là full-stack engineer phụ trách mở rộng website đã có trong repo này.

## Bước 1 - kiểm thử
- Giữ nguyên trang chủ và tính năng vẽ, map, chỉnh ảnh hiện tại.
- Kiểm tra lỗi console trên Chrome/Firefox, kiểm thử touch/pointer và mobile.
- Không commit secret vào repo. Chỉ dùng assets có quyền sử dụng.

## Bước 2 - Map Studio HD
- Hỗ trợ layer nền/đồ vật/collision, import PNG tileset 32/64/128px; snapping, zoom, pan, undo/redo.
- Tách map lv1-5 và lv6-12 thành 2 project có tilemap đa lớp.
- Thư viện sprite, nhà 2 tầng, cầu, rừng và tương tác.
- Export Godot 4 bằng dữ liệu tương thích TileSet/TileMapLayer (thêm mã import GDScript nếu cần).

## Bước 3 - Pixel & spritesheet
- Bút, tẩy, bucket, eyedropper, chọn vùng, frame timeline, onion skin, xuất sprite sheet PNG/JSON.
- Chế độ chibi HD tách layer và chỉnh khung hình bằng Canvas.

## Bước 4 - AI thực
- Backend Node/Python tùy lựa chọn; provider adapter cho dịch vụ tạo ảnh được hỗ trợ.
- API key từ secret/environment trên server, không để ở client hoặc git.
- Endpoint kiểm soát xác thực, rate limit, hạn mức, xử lý lỗi.
- Khi chưa cấu hình provider phải hiển thị trạng thái chưa kết nối, không giả vờ tạo ảnh.

## Bước 5 - triển khai
- Frontend deploy GitHub Pages miễn phí, backend triển khai riêng theo nhà cung cấp.
- Viết README rõ các bước. Không được thay website bằng mockup.
- Chạy test/build/check link trước khi kết thúc.
