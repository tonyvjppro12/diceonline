# 🎲 HƯỚNG DẪN SỬ DỤNG ONLINE-DICE (KHÔNG CẦN BẬT SERVER)

Phiên bản này đã được nâng cấp lên **Serverless Cloud Sync**:
- **KHÔNG CẦN** mở Command Prompt (cmd) hay PowerShell.
- **KHÔNG CẦN** chạy file `python server.py`.
- **KHÔNG CẦN** mở máy tính trước hay dùng ngrok / localtunnel.
- **KHÁC MẠNG VẪN CHẠY VÔ TƯ**: Máy livestream ở nhà cắm mạng dây, điện thoại bật 4G/5G ở bất kỳ đâu đều kết nối và điều khiển xúc xắc tức thì (độ trễ < 80ms).

---

## 🚀 2 CÁCH DÙNG

### CÁCH 1: Dùng trực tiếp trên máy tính & điện thoại (Dễ nhất)

1. **Trên máy tính livestream**:
   - Nhấp đúp chuột mở file `index.html` bằng trình duyệt (Chrome, Edge, Cốc Cốc,...).
   - Trang xúc xắc hiện lên bình thường, góc dưới có kết nối Cloud tự động.

2. **Mở Admin Panel bí mật trên máy tính (nếu muốn chỉnh)**:
   - Nhấn **`Ctrl + Shift + F12`** hoặc **click 5 lần vào logo ONLINE-DICE.COM**.
   - Nhập PIN: **`8888`**

3. **Trên điện thoại (Remote điều khiển từ xa)**:
   - Gửi file `remote.html` sang điện thoại và mở lên, hoặc đưa lên web (xem Cách 2).
   - Nhập PIN: **`8888`** để mở bảng điều khiển.
   - Nhấn nút **🎲 ROLL TRÊN MÁY TÍNH !** hoặc chạm đổi màu bất kỳ -> Trên màn hình livestream đổi ngay lập tức!

---

### CÁCH 2: Đưa lên Web miễn phí vĩnh viễn (Khuyên dùng để có link trên điện thoại)

Bạn chỉ cần kéo thả cả thư mục này lên dịch vụ hosting tĩnh miễn phí:

1. Vào trang: **[https://app.netlify.com/drop](https://app.netlify.com/drop)** (Không cần code, hoàn toàn miễn phí).
2. Kéo cả thư mục `online-dice` thả vào ô upload.
3. Trong 5 giây bạn sẽ nhận được một đường link web, ví dụ: `https://ten-ban-chon.netlify.app`.

Khi đó:
- **Link cho khán giả / màn hình livestream**: `https://ten-ban-chon.netlify.app`
- **Link remote cho bạn cầm điện thoại**: `https://ten-ban-chon.netlify.app/remote.html` (Nhập PIN 8888 để điều khiển)

---

## 🔒 BẢO MẬT PHÒNG RIÊNG (ROOM ID)

- Mặc định mã phòng bí mật là: **`dice8888`**
- Nếu bạn muốn đổi sang mã phòng riêng (ví dụ `myroom123`):
  - Trong Owner Panel mục 6 trên `index.html`, đổi sang `myroom123`.
  - Trên `remote.html`, đổi sang cùng mã `myroom123` là kết nối riêng tư 1-1, không ai can thiệp được.

---

## 🎨 DANH SÁCH TÍNH NĂNG
1. **🎯 CÀI SẴN KẾT QUẢ ROLL TỪ XA QUA REMOTE (MỚI)**:
   - **Chỉnh số lượng xúc xắc (1 đến 6) tức thì**: Trên remote có 6 nút chọn số xúc xắc to rõ (`1 Die`, `2 Dice`, `3 Dice`, `4 Dice`, `5 Dice`, `6 Dice`), chạm 1 cái là máy tính live đổi số lượng xúc xắc ngay.
   - **Gán màu kết quả cho từng viên**:
     - Remote tự động hiển thị thẻ cho từng viên tương ứng (ví dụ 4 viên: Viên 1, Viên 2, Viên 3, Viên 4).
     - Muốn Viên 1 ra màu gì? Chạm Viên 1 $\rightarrow$ Chạm màu đó (`Red`, `Orange`, `Yellow`, `Green`, `Blue`, `Purple`).
     - Tự động nhảy (Auto-advance): Chọn xong Viên 1 tự động chuyển sang Viên 2, 3, 4. Chỉ mất 2 giây để gán xong cả bộ.
     - Nút Combo 1-chạm: `🌈 Rainbow (Cầu vồng)`, `🔴 Toàn Đỏ`, `🟠 Toàn Cam`, `🟡 Toàn Vàng`, `🟢 Toàn Xanh lá`, `🔵 Toàn Xanh dương`, `🟣 Toàn Tím`.
   - **Hiệu ứng trên Livestream chân thực 100%**:
     - Khi bấm **🎲 ROLL** (dù bấm trên điện thoại hay người trên máy tính bấm *Go Again !*):
     - Xúc xắc tung lên, xoay vòng, nảy bật đa va chạm và có tiếng xúc xắc sống động như ngẫu nhiên thật.
     - **Nhưng khi dừng lại**: Các viên xúc xắc sẽ dừng **CHÍNH XÁC** ở các màu bạn đã chọn trên điện thoại!
     - Khán giả xem live hoàn toàn không nhận ra kết quả đã được cài trước.
   - **Nút chuyển chế độ `🎯 Cài sẵn` / `🎲 Ngẫu nhiên`**: Khi muốn một lượt đổ xúc xắc hoàn toàn tự nhiên ngẫu nhiên, chỉ cần chuyển sang `🎲 Ngẫu nhiên`.
2. **⚡ Tùy chỉnh tốc độ lăn xúc xắc trên điện thoại**:
   - 6 nút chọn nhanh: Cực nhanh (0.4s), Nhanh (0.7s), Chuẩn (1.0s), Chậm (1.8s), Hồi hộp (2.6s), Rất chậm (3.5s).
   - Thanh trượt tùy chỉnh chi tiết từ 0.3s đến 3.5s.
   - Hiệu ứng nảy đa va chạm và tiếng xúc xắc tự co dãn theo thời gian thực (lăn chậm thì va chạm nảy nhiều lần, giảm tốc dần hồi hộp).
3. **15 Theme bàn đổ**: Blue, Sab-Blue, Green, Sab-Green, Red, Sab-Red, Pink, B&W, Sab-Black, Heaven, Hell, Underwater, Bronze, Silver, Gold.
4. **Âm thanh tiếng xúc xắc thật**: Giả lập đa va chạm (bounces), cộng hưởng vang mặt bàn (convolver reverb), tiếng thud khi xúc xắc dừng.
5. **Mục số 5 - Custom Face Colors**: Đổi mã màu Hex cho từng mặt từ 1 đến 6.
6. **Chế độ 6-sided Dice & Color Dice**.
7. **Nút Admin ẩn 100%**: Người xem livestream không bao giờ thấy nút Admin.
8. **📜 Lịch sử ra màu & Thống kê 6 màu (MỚI)**:
   - **Bảng lịch sử trên màn hình Live (`index.html`)**: Hiển thị thứ tự lượt `#1, #2...`, thời gian chính xác, các chip màu đã ra kèm tổng kết (ví dụ: `1 Red, 2 Green, 1 Blue`).
   - **Thanh thống kê tỷ lệ 6 màu**: Đếm dồn số lần xuất hiện của Red, Orange, Yellow, Green, Blue, Purple theo thời gian thực để người xem live theo dõi cầu màu.
   - **Màn hình Remote trên điện thoại (`remote.html`)**:
     - Khung **🎯 KẾT QUẢ VỪA RA** nổi bật ngay dưới nút ROLL, cập nhật tức thì khi xúc xắc dừng.
     - Tự động rung điện thoại (haptic vibration) phản hồi khi có kết quả.
     - Lịch sử đầy đủ các lượt lắc kèm 6 ô thống kê mini và nút **🗑 Xóa lịch sử** 1-chạm.
   - **Đồng bộ 2 chiều qua Cloud**: Lắc trên máy tính hay điện thoại thì cả 2 thiết bị đều cập nhật lịch sử đồng thời.
   - **Tùy chọn ẩn/hiện trên Live**: Trong Admin Panel mục 7 có ô checkbox cho phép streamer bật/tắt hiển thị lịch sử trên màn hình livestream tùy ý.
