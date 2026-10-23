# 🚀 Người Que Tránh Tên Lửa - Mobile APK Repository

Kho lưu trữ này chứa toàn bộ mã nguồn và cấu hình để tạo file cài đặt **APK** cho trò chơi điện thoại **Người Que Tránh Tên Lửa (Rocket Strike)** thông qua **GitHub Actions** hoàn toàn tự động.

## ✨ Điểm nổi bật trong phiên bản này:
1. **Nút điều khiển cảm ứng trực quan trên màn hình**:
   - **Chế độ 1 người (Solo / VS AI)**: Hiển thị **1 vòng tròn điều khiển (Joystick)** và các nút Nhảy, Kỹ năng đặc biệt.
   - **Chế độ 2 người chơi (2P)**: Hiển thị **2 vòng tròn điều khiển** (mỗi người 1 bên màn hình) để 2 người chơi cùng điều khiển trên một điện thoại!
2. **Kỹ năng đặc biệt (Skills)**:
   - Nút năng lượng ⚡ trên màn hình cho phép người chơi kích hoạt các kỹ năng ngẫu nhiên thú vị:
     - **Quantum Dash**: Lướt dịch chuyển nhanh né đạn chớp nhoáng.
     - **Shockwave**: Tạo sóng năng lượng đẩy lùi các tên lửa xung quanh.
     - **Time Warp**: Làm chậm toàn bộ tên lửa trong 4 giây.

---

## 🛠️ Hướng dẫn tạo file APK tự động trên GitHub:

1. **Tạo Repository mới trên GitHub**:
   - Truy cập [GitHub](https://github.com) và tạo một repository mới (ví dụ: `rocket-strike-apk`).
2. **Tải lên các file**:
   - Giải nén file ZIP này và đẩy (push) toàn bộ thư mục và file lên repository GitHub của bạn.
3. **Tải file APK**:
   - Nhấp vào mục **Actions** trên thanh menu repository GitHub của bạn.
   - Chọn workflow **Build Android APK** đang chạy (hoặc đã hoàn thành).
   - Tại phần **Artifacts** ở dưới cùng, tải xuống file `rocket-strike-debug-apk.zip`, giải nén để nhận file `app-debug.apk` cài đặt lên điện thoại Android của bạn!
