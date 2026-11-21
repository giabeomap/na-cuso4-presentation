# BÀI THUYẾT TRÌNH HÓA HỌC 9: PHẢN ỨNG GIỮA NATRI VÀ DUNG DỊCH ĐỒNG(II) SUNFAT (CuSO₄)
**Chuẩn Thiết Kế:** *Premium Glassmorphism 2026*  
**Dành cho:** Học sinh Lớp 9 & Giáo viên bộ môn Hóa học THCS  
**Tác giả:** Trợ lý Antigravity AI (Google DeepMind)

---

## 🌟 ĐẶC ĐIỂM NỔI BẬT

1. **Thiết kế Kính Mờ Đa Tầng (Multi-layered Glassmorphism):**
   - Đạt tiêu chuẩn thẩm mỹ cao cấp 2026: backdrop blur 20px - 40px, viền kính phản quang vi tế (`border: 1px solid rgba(255,255,255,0.18)`), bóng mờ phân tầng đa lớp.
   - Bảng màu hóa học sống động: Xanh lam sâu thẳm của dung dịch $CuSO_4$ (`#0ea5e9`, `#2563eb`), ánh bạc kim loại của Natri (`#f1f5f9`), và cam hổ phách phát sáng khi phản ứng tỏa nhiệt mạnh (`#f59e0b`).
   - Hiệu ứng hạt nền trôi nổi (particle canvas background) và ánh sáng ambient lighting chuyển động chậm tạo chiều sâu 3D.

2. **Video Thí Nghiệm Đã Tải Về & Tích Hợp Sẵn (Hoàn toàn Offline):**
   - File video: `video_experiment.mp4` (độ phân giải 1080p, dài 81.4 giây, âm thanh trung thực).
   - **Đã cắt bỏ hoàn toàn phần câu hỏi và bài giảng bảng phấn cuối video** theo đúng yêu cầu (kết thúc ngay khi kết thúc quan sát cốc thí nghiệm ở 81.4s, trước khi chuyển sang bảng viết).
   - **Trình phát video Glassmorphic Video Player tùy biến:**
     - Các nút điều khiển kính mờ sang trọng: Play/Pause, tua thanh trượt (seek bar), hiển thị thời gian, chỉnh tốc độ phát (`0.5x`, `1.0x`, `1.25x`, `1.5x`, `2.0x`), âm lượng, toàn màn hình.
     - **4 Điểm mốc quan sát (Timeline Bookmarks):** Bấm nhảy nhanh tới:
       - `00:10`: Chuẩn bị & Cắt mẩu Natri
       - `00:26`: Cho Na vào dung dịch $CuSO_4$
       - `00:40`: Na nóng chảy vo tròn thành viên bi chạy tròn, sủi bọt khí $H_2$
       - `00:55`: Xuất hiện kết tủa xanh lam $Cu(OH)_2$ lơ lửng rồi lắng dần
     - Hỗ trợ đổi 3 góc quay camera (Góc chính 81s, Góc cận cảnh phóng đại hạt Na 124s, Góc ống nghiệm 94s).

3. **Phòng Thí Nghiệm Ảo Tương Tác 60 FPS (Interactive Canvas Simulation):**
   - Mô phỏng vật lý chân thực: Hạt Natri rơi chìm nhẹ rồi nổi ngay do khối lượng riêng nhỏ hơn nước ($D_{Na} \approx 0.97 \text{ g/cm}^3 < D_{H_2O} \approx 1.0 \text{ g/cm}^3$).
   - Phản ứng tỏa nhiệt làm Natri nóng chảy ($97.8^\circ C$) thành giọt cầu bạc sáng loáng.
   - Luồng khí $H_2$ phụt đẩy hạt Natri chuyển động hỗn loạn trên bề mặt dung dịch.
   - Các đám mây kết tủa xanh lơ $Cu(OH)_2$ xuất hiện dày đặc quanh hạt Na và chìm từ từ xuống đáy.
   - Nhiệt kế kỹ thuật số đo nhiệt độ thực tế tăng từ $25^\circ C$ lên $> 95^\circ C$.

4. **Trắc Nghiệm Tương Tác & Chấm Điểm Tức Thì (Grade 9 Quiz):**
   - 3 câu hỏi then chốt phá tan ngộ nhận kinh điển lớp 9 ("Natri đẩy Cu kim loại màu đỏ ra khỏi muối").
   - Hiệu ứng âm thanh sinh động (Web Audio API) và pháo hoa giấy chúc mừng (Canvas Confetti).

5. **Slide Nhận Xét Hiện Tượng & Cơ Chế 2 Giai Đoạn Chuẩn Sách Giáo Khoa:**
   - Phân tích chi tiết 4 hiện tượng quan sát kèm hình họa minh họa.
   - Phương trình phản ứng 2 bước:
     1. $2Na + 2H_2O \rightarrow 2NaOH + H_2 \uparrow$
     2. $2NaOH + CuSO_4 \rightarrow Cu(OH)_2 \downarrow \text{ (xanh lơ)} + Na_2SO_4$
     - Tổng quát: $2Na + 2H_2O + CuSO_4 \rightarrow Cu(OH)_2 \downarrow + Na_2SO_4 + H_2 \uparrow$
   - Nhấn mạnh quy tắc vàng: **Không bao giờ có kim loại Cu đỏ xuất hiện!**

---

## 🚀 HƯỚNG DẪN TRÌNH CHIẾU

### Cách 1: Mở Trực Tiếp Trình Duyệt
Nhấp đúp chuột vào file `index.html` trong thư mục này để mở bằng Chrome, Edge, Brave hoặc Firefox.

### Cách 2: Xem Qua Localhost (Khuyên Dùng Để Video Chạy Mượt Nhất)
Server nội bộ đang chạy sẵn tại địa chỉ:
👉 **`http://localhost:8085/index.html`**

Nếu server tắt, bạn có thể khởi động lại bằng lệnh:
```bash
python -m http.server 8085 --directory "C:\Users\Huynh Gia Bao\.gemini\antigravity\scratch\na-cuso4-presentation"
```

---

## ⌨️ CÁC PHÍM TẮT ĐIỀU KHIỂN CHUYÊN NGHIỆP

| Phím Tắt | Chức Năng |
| :--- | :--- |
| `Space` / `→` / `PageDown` | Chuyển sang slide tiếp theo |
| `←` / `PageUp` | Quay lại slide trước |
| `F` | Bật / tắt chế độ Trình Chiếu Toàn Màn Hình (Fullscreen) |
| `O` | Bật / tắt chế độ Tổng Quan Lưới Slide (Slide Grid Overview) |
| `N` | Mở Ghi Chú Thuyết Trình Dành Cho Giáo Viên / Người Thuyết Trình |
| `L` | Mở nhanh Thí Nghiệm Ảo 2D (Slide 5) |
| `Home` / `End` | Về slide đầu tiên / Nhảy tới slide kết thúc |
| `Space` *(khi ở Slide 4)* | Phát / Tạm dừng video thí nghiệm |
| `1` - `9`, `0` | Nhảy trực tiếp tới Slide 1 đến Slide 10 |

---

## 📁 CẤU TRÚC THƯ MỤC DỰ ÁN

```
na-cuso4-presentation/
├── index.html              # File trình chiếu HTML chính (tích hợp đầy đủ CSS, JS)
├── video_experiment.mp4    # Video thí nghiệm 81.4s (đã cắt bỏ phần câu hỏi cuối)
├── video_poster.jpg        # Ảnh bìa preview cho trình phát video
├── video_close_up.mp4      # Video góc quay cận cảnh bổ trợ (124s)
├── thay_quyen.mp4          # Video góc quay thí nghiệm ống nghiệm bổ trợ (94s)
├── build.py                # File script Python tạo và cập nhật index.html
└── README.md               # Tài liệu hướng dẫn sử dụng chi tiết
```

Chúc bạn có một buổi thuyết trình Hóa học 9 thật ấn tượng, trực quan và đạt điểm số tối đa!
