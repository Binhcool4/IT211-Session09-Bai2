# Phân tích Log Levels

## 1. Áp dụng mã giảm giá thành công
- Log Level: INFO
- Lý do:
    - Đây là luồng hoạt động bình thường của hệ thống.
    - Chỉ mang tính ghi nhận hành vi thành công.

## 2. Người dùng nhập mã hết hạn hoặc mã sai
- Log Level: WARN
- Lý do:
    - Không phải lỗi hệ thống.
    - Hệ thống vẫn hoạt động bình thường.
    - Chỉ là cảnh báo về dữ liệu đầu vào hoặc lỗi nghiệp vụ.

## 3. Lỗi mất kết nối database hoặc lỗi logic hệ thống
- Log Level: ERROR
- Lý do:
    - Đây là lỗi nghiêm trọng cần Dev xử lý.
    - Có thể làm chức năng hoạt động sai hoặc ngừng hoạt động.