# Hệ thống báo thức điều khiển giọng nói (Audio-KWS)

## 1. Thông tin sinh viên
- **Họ và tên:** Lê Ngọc Yến Nhi
- **MSSV:** N23DCCI052
- **Lớp:** D23CQCI01-N
- **Đề tài:** Nhận dạng từ khóa giọng nói ứng dụng cho hệ thống báo thức thông minh sử dụng Edge Impulse.

## 2. Mô tả thư mục (Repository Structure)
- Chứa các tệp mã nguồn (.js, .wasm, .html, .py) được xuất từ Edge Impulse dưới dạng WebAssembly.
- Các tệp dữ liệu âm thanh mẫu (Sample Data) để kiểm thử.

## 3. Các phụ thuộc (Dependencies)
- Python 3.x (để chạy server ảo nội bộ).
- Trình duyệt web hiện đại (Chrome/Edge/Firefox) hỗ trợ WebAssembly.
- Microphone kết nối với máy tính.

## 4. Hướng dẫn cài đặt và chạy (How to Run)
1. Tải toàn bộ mã nguồn về máy tính.
2. Mở Terminal / Command Prompt tại thư mục chứa mã nguồn.
3. Chạy lệnh: `python server.py` (hoặc `python3 server.py`).
4. Mở trình duyệt web và truy cập vào địa chỉ: `http://localhost:8000`.
5. Cấp quyền truy cập Microphone và bắt đầu đọc các từ khóa (yen_nhi, bao_thuc, tat_bao, snooze).
