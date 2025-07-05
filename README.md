# 🌐 IoT Cloud Simulator – Upload/Download dữ liệu IoT với Log thời gian

Dự án mô phỏng quá trình **upload và download dữ liệu từ các thiết bị IoT lên hệ thống cloud giả lập**, sử dụng các kỹ thuật mã hóa cơ bản để đảm bảo tính bảo mật và toàn vẹn dữ liệu.

---

## 📦 Chức năng chính

- 📤 **Upload dữ liệu IoT** (nhiệt độ, độ ẩm, v.v...) kèm mã hóa AES-GCM và chữ ký RSA.
- 📥 **Download dữ liệu IoT** với xác thực chữ ký và kiểm tra toàn vẹn hash.
- 🔐 **Bảo mật mô phỏng**:
  - Mã hóa: **AES-GCM 256-bit**
  - Chữ ký số: **RSA 1024-bit + SHA-512**
  - Hash kiểm tra toàn vẹn: **SHA-512**
- 🧾 **Ghi log thời gian và hoạt động** trong suốt quá trình truyền tải.
- 🎲 Tạo dữ liệu cảm biến mẫu để thử nghiệm.

---

## 🧪 Công nghệ sử dụng

- HTML + CSS + JavaScript (thuần)
- Không dùng server thật, mọi xử lý đều chạy trong trình duyệt
- Mã hóa và giả lập lưu trữ hoàn toàn client-side (cloudStorage)

---

## 🚀 Cách sử dụng

1. Mở file `test1.html` bằng trình duyệt (Chrome/Edge khuyến nghị).
2. Chọn loại cảm biến và nhập (hoặc tạo) dữ liệu.
3. Nhấn "📤 Upload dữ liệu" để gửi lên cloud.
4. Chọn file từ danh sách và nhấn "📥 Download dữ liệu" để nhận lại.
5. Quan sát log ghi lại toàn bộ quá trình ở cuối trang.

---

## 📂 Cấu trúc file

| File | Mô tả |
|------|-------|
| `Main.html` | Giao diện giả lập + toàn bộ mã JavaScript xử lý upload/download |

---

## 📌 Ghi chú

- Đây là hệ thống **giả lập phục vụ học tập/demo**, không kết nối thật với cloud hay IoT device.
- Phù hợp cho các môn học như: **An toàn bảo mật thông tin**, **IoT cơ bản**, **Mạng máy tính**.

---


## 📜 Giấy phép

MIT License – sử dụng tự do cho mục đích học tập và cá nhân.
