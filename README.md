# tim-ten-backdrop
Cho phép runner chụp ảnh trực tiếp tấm bạt backdrop vật lý trước mặt, sau đó hệ thống tự động quét và highlight (khoanh vùng) tên của họ ngay trên tấm hình đó
# Tech Stack
- OCR (Nhận diện chữ): Tesseract.js (Thư viện OCR bằng Javascript phổ biến nhất, bản chất là cổng từ Tesseract C++ sang WebAssembly, chạy trực tiếp trên browser).
- Xử lý & Hiển thị ảnh: HTML5 Canvas API để vẽ ảnh và vẽ ô vuông highlight (bounding box) lên tên của runner.
