# 🎲 HƯỚNG DẪN SỬ DỤNG ONLINE-DICE (GIAO DIỆN CHUẨN 100% ONLINE-DICE.COM)

Phiên bản này đã được thiết kế lại **chuẩn 100% giao diện và phong cách của Online-Dice.com (Chủ đề SAB-BLU / Roblox Pet Simulator)**:
- **Giao diện 3 cột card xanh nổi**:
  - **Cột trái**: `OUR TOP STREAMERS` (7 streamer nổi tiếng kèm avatar, huy hiệu `Live` đỏ, tích xanh verified, name và handle).
  - **Cột giữa**: `ROLL COLOR DICE`
    - 3 Dropdown chuẩn: `4 DICE ⌄`, `COLOR D ⌄`, `SAB-BLU ⌄`.
    - Dàn xúc xắc màu bo góc viền trắng 3.5px chuẩn xác với chấm tròn trắng ở giữa.
    - Mã lượt quay: `ID: eBI525zQG2` (tự đổi seed sau mỗi lần lắc).
    - Nút trắng bo tròn: `⏱ Verify History` mở bảng thống kê tỷ lệ ra 6 màu và lịch sử lượt lắc.
    - Banner quảng cáo Creative Cloud Pro ở dưới.
  - **Cột phải**: `OUR TOP STREAMERS` (7 streamer top tiếp theo).
- **Hình nền**: Voxel Roblox sky world, mây 3D khối, chú mèo voxel bay, cây cọ khối và cổng lego nâu hai bên.
- **Serverless Cloud Sync**: Kết nối tức thì không cần cài đặt server hay mở cmd.
- **Khác mạng vẫn điều khiển mượt mà**: Máy tính live dùng WiFi/dây, điện thoại bật 4G/5G vẫn gài màu và lắc tức thì.

---

## 🚀 2 CÁCH DÙNG

### CÁCH 1: Dùng trực tiếp trên máy tính & điện thoại (Dễ nhất)

1. **Trên máy tính livestream**:
   - Nhấp đúp chuột mở file `index.html` bằng trình duyệt (Chrome, Edge, Cốc Cốc,...).
   - Trang xúc xắc hiện lên bình thường, góc dưới có kết nối Cloud tự động.

2. **Mở Admin Panel trên máy tính**:
   - **Phím tắt 1-chạm (Dễ nhất, nhạy 100%)**:
     - Nhấn phím **`A`** (hoặc `a`) trên bàn phím.
     - Hoặc nhấn phím **`~`** (dấu ngã / backtick cạnh số 1).
     - Hoặc nhấn **`Ctrl + M`** / **`F2`** / **`Ctrl + Shift + A`**.
   - **Cheat code bí mật khi Livestream**:
     - Gõ liên tiếp chữ **`admin`** ở bất kỳ đâu trên bàn phím $\rightarrow$ Admin panel tự động mở!
   - **Click chuột**:
     - Nhấp đúp chuột (Double click) vào logo **ONLINE-DICE.COM**.
     - Hoặc bấm vào nút **`⚙ Admin`** ở góc trên bên phải thanh navbar / nút tròn nổi ở góc dưới bên phải / link ở chân trang.
   - **Mở qua link**:
     - Thêm **`?admin=1`** vào link web (Ví dụ: `index.html?admin=1`) $\rightarrow$ Tự động mở ngay khi vừa tải trang!
   - **Nhập mã PIN**: **`8888`** (đổi mã mới trong mục 6).
   - **Đóng Admin**: Bấm phím **`Esc`** hoặc click ra ngoài vùng tối.

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

## 🔒 BẢO MẬT & ĐỔI MẬT KHẨU / MÃ PHÒNG (ROOM ID)

Hệ thống có **2 lớp bảo mật**:

### 1. Mã phòng bí mật (Room ID) — "Kênh kết nối riêng tư":
- Mặc định là: **`dice8888`**
- Chỉ các máy có cùng mã phòng mới kết nối và điều khiển được nhau.
- **Cách đổi**:
  - **Trên điện thoại (`remote.html`)**: Ở thẻ dưới cùng *"🔒 Bảo mật: Mã phòng & Mật khẩu PIN"*, nhập mã phòng mới (ví dụ: `phongcuatui123`) $\rightarrow$ bấm **Đổi phòng**.
  - **Trên máy tính (`index.html`)**: Mở Admin Panel (click logo 5 lần hoặc `Ctrl+Shift+F12`), mục 6 nhập cùng mã phòng `phongcuatui123` $\rightarrow$ bấm **Save Settings**.
  - **Hoặc truyền trực tiếp qua link**:
    - Máy live: `https://ten-web.netlify.app/?room=phongcuatui123`
    - Điện thoại: `https://ten-web.netlify.app/remote.html?room=phongcuatui123`

### 2. Mật khẩu PIN mở khóa (PIN Code):
- Mặc định ban đầu là: **`8888`**
- Dùng để ngăn người khác mở bảng điều khiển bí mật.
- **Cách đổi ngay trên giao diện (Không cần sửa code)**:
  - **Trên điện thoại**: Ở thẻ dưới cùng, ô *"Đổi Mật khẩu PIN mở Remote"*, gõ mật khẩu mới (ví dụ `1234`, `9999`...) $\rightarrow$ bấm **Lưu PIN**.
  - **Trên máy tính**: Trong Admin Panel mục 6, ô *"Đổi Mật khẩu PIN mở khóa"*, nhập mã mới $\rightarrow$ bấm **Lưu PIN**.
  - **Mẹo mở Remote tự động không cần gõ PIN**: Thêm `?pin=8888` vào đuôi link điện thoại (ví dụ: `remote.html?pin=8888`), trang web sẽ tự động mở thẳng vào bàn điều khiển mà không cần nhập PIN!

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
7. **ẨN HOÀN TOÀN NÚT ADMIN TRÊN LIVE (CHẾ ĐỘ LIVESTREAM BÍ MẬT)**:
   - **Bật/Tắt ngay trong Admin Panel (`index.html`)**: Có ô checkbox *"Ẩn nút Admin & thanh trạng thái (Chế độ Livestream bí mật)"*. Khi tích chọn, nút ⚙ và thanh trạng thái biến mất 100%, người xem live hoàn toàn không biết có bảng cài đặt.
   - **Bật/Tắt từ xa trên điện thoại (`remote.html`)**: Trong mục bảo mật có nút *"Ẩn nút Admin"*, bấm 1 cái là nút ⚙ trên màn hình live biến mất ngay lập tức.
   - **Cách mở lại Admin khi đang ẩn nút**: Chỉ cần nhấn phím **`A`** (hoặc **`~`**, **`F2`**, **`Ctrl + M`**) trên bàn phím, hoặc **nhấp chuột 3 lần** vào tiêu đề **`ROLL COLOR DICE`** trên màn hình!
8. **📜 Lịch sử ra màu & Thống kê 6 màu (MỚI)**:
   - **Bảng lịch sử trên màn hình Live (`index.html`)**: Hiển thị thứ tự lượt `#1, #2...`, thời gian chính xác, các chip màu đã ra kèm tổng kết (ví dụ: `1 Red, 2 Green, 1 Blue`).
   - **Thanh thống kê tỷ lệ 6 màu**: Đếm dồn số lần xuất hiện của Red, Orange, Yellow, Green, Blue, Purple theo thời gian thực để người xem live theo dõi cầu màu.
   - **Màn hình Remote trên điện thoại (`remote.html`)**:
     - Khung **🎯 KẾT QUẢ VỪA RA** nổi bật ngay dưới nút ROLL, cập nhật tức thì khi xúc xắc dừng.
     - Tự động rung điện thoại (haptic vibration) phản hồi khi có kết quả.
     - Lịch sử đầy đủ các lượt lắc kèm 6 ô thống kê mini và nút **🗑 Xóa lịch sử** 1-chạm.
   - **Đồng bộ 2 chiều qua Cloud**: Lắc trên máy tính hay điện thoại thì cả 2 thiết bị đều cập nhật lịch sử đồng thời.
   - **Tùy chọn ẩn/hiện trên Live**: Trong Admin Panel mục 7 có ô checkbox cho phép streamer bật/tắt hiển thị lịch sử trên màn hình livestream tùy ý.
9. **🎮 BỘ TIỆN ÍCH GAMING & BẢNG `YOUR LAST 20 ROLLS` CHUẨN 100% (MỚI CẬP NHẬT)**:
   - **Bộ đếm điểm / cược `[-1 -10 | 0 | +1 +10]`**: Nằm trong thẻ giữa, streamer có thể bấm `-1`, `-10`, `+1`, `+10` để đếm cược hoặc điểm thắng/thua. Nhấp đúp vào số giữa để reset về 0.
   - **Chuỗi lắc liên tiếp**: `Roll Streak: 10 ⚡ 🎲 (Charged dice)` tự động cộng dồn sau mỗi lượt đổ xúc xắc.
   - **Đếm người xem trực tuyến**: `🟢 Users online: 589` tự động dao động chân thực quanh mốc 580 - 615.
   - **Nút cài đặt app**: `INSTALL APP (Fewer ads, instant access.)`.
   - **Dòng màu sắc**: `Possible colors are: Red, Orange, Yellow, Green, Blue and Purple.` với chữ nhiều màu nổi bật.
   - **Bảng xác suất**: Link `See your chances of winning →` bấm vào mở bảng xác suất toán học chi tiết.
   - **Công tắc chống ban**: `Anti-Ban Mode` công tắc gạt bật/tắt tiện lợi.
   - **Bảng `YOUR LAST 20 ROLLS` chuẩn theo ảnh**:
     - `STATS:` hiển thị huy hiệu cúp vàng `🏆` cho màu ra nhiều nhất (`🟥 x8 🏆`, `🟩 x8`, `🟪 x7`, `🟧 x7`, `🟨 x4`, `🟦 x3`).
     - `LONGEST STREAK:` hiển thị chuỗi dài nhất kèm biểu tượng lửa (`🟥 x3 🔥`).
     - `THIS ROLL:` Lượt 1 mới nhất với 4 xúc xắc màu bo góc viền trắng chấm tròn giữa.
     - `PREVIOUS ROLLS:` Các lượt từ 2 đến 20 ngăn cách bằng đường nét đứt màu trắng.
     - Hiển thị cả khi cuộn xuống ở thẻ giữa và khi bấm nút `⏱ Verify History`!

10. **🟡 NÚT `GO AGAIN !` & DÀN 10 STREAMER MỖI BÊN (CHUẨN 100% THEO ẢNH MỚI NHẤT)**:
    - **Nút bấm `GO AGAIN !` màu vàng kim nổi bật**: Nằm ngay dưới banner quảng cáo FxPro ở thẻ giữa. Thiết kế bo tròn viền sáng gradient vàng cam `#ffd000` -> `#ffba00` với chữ trắng in hoa đậm. Nhấp vào là xúc xắc lăn ngay lập tức kèm hiệu ứng và âm thanh sống động.
    - **Banner quảng cáo FxPro Trade**: Hiển thị hình ảnh quảng cáo FxPro Trade chân thực chuẩn 100% như trên website gốc.
    - **Đầy đủ 10 Streamer mỗi bên**:
      - **Cột trái (10 Streamer)**: `DEETS GAMING` (verified), `RIP_GUUH` (verified), `MELIODASGBS` (verified), `RIKKYWRLD` (verified), `VLX` (verified), `YAGUIN` (verified), `WAVY` (verified), `O SHAOLIN` (verified), `KENZSTREAM` (verified), `MOPTRADES`.
      - **Cột phải (10 Streamer)**: `MRPROFITER`, `FALLINSINZ`, `NACHOSINO`, `3XBLAZE`, `ECLIPSEFR`, `IMBADWTW`, `FREXX` (verified), `VINYYWS` (verified), `XNSZN` (verified), `XOTIC` (verified).
      - Tất cả đều có ảnh avatar chuẩn lấy trực tiếp từ ảnh chụp, huy hiệu đỏ `Live`, tên tài khoản `@handle` và huy hiệu tích xanh xác nhận.

11. **🎲 HIỂN THỊ CỤC DICE MÀU TRÊN REMOTE & TỶ LỆ RA ĐẦY ĐỦ 6 MÀU**:
    - **Lịch sử hiển thị cục Dice màu 3D chuẩn xác**: Thay thế toàn bộ mã chữ `#undefined` và chuỗi hex `#ff7700` bằng cục xúc xắc mini bo góc có viền trắng và chấm tròn trắng ở giữa (`.r-dice-cube`).
    - **Tỷ lệ ra tất cả các màu khi quay bất kỳ số lượng xúc xắc (1 đến 6 viên)**:
      - Mặc định ở chế độ **`🎲 Ngẫu nhiên`**: Dù bạn chọn quay 1 viên, 2 viên, 3 viên, 4 viên, 5 viên hay 6 viên, mỗi viên xúc xắc đều có tỷ lệ xuất hiện độc lập, đồng đều (1/6 = 16.67%) của tất cả 6 màu có trên web: **Red, Orange, Yellow, Green, Blue, Purple**.
      - Khi muốn gài kết quả màu cụ thể: Chỉ cần bấm chuyển sang **`🎯 Cài sẵn`** trên Remote để gán màu theo ý muốn.
