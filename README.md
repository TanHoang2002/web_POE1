# GeGe Team — Path of Exile 1

Trang dịch vụ Path of Exile 1 của GeGe Team (Nhà Cáo), cùng khuôn với trang WoW Forever. Mở `index.html` để xem.

- 5 ngôn ngữ (English mặc định, Tiếng Việt, Bahasa Indonesia, Filipino, Русский), chọn ở nút địa cầu.
- Thu mua Divine Orb (0,115 USDT) và Mirror of Kalandra (460 USDT = 4.000 Divine), chỉ tính bằng USDT; có máy tính số lượng → tổng USDT.
- Dịch vụ: cày cấp & campaign, Labyrinth, mở Atlas, farm map & boss, mua bán item hộ, đơn theo yêu cầu. Giá thương lượng.
- Mỗi dịch vụ có trang chi tiết với biểu mẫu và bản tóm tắt đơn để gửi qua Zalo / Fanpage. Trang không nhận tiền.
- Link mở thẳng dịch vụ: `?svc=divine|mirror|leveling|lab|atlas|farm|items|custom`, chọn ngôn ngữ: `?lang=en|vi|id|fil|ru`.

## Sửa nội dung

Trong thẻ `<script>` của `index.html`:

- `DIV_USDT`, `MIRROR_DIV`: rate thu mua.
- `PRODUCTS`: danh sách dịch vụ (ảnh, danh mục, loại). `featured: true` thì hiện ở "Ưu đãi nổi bật".
- `I18N` (chữ giao diện) và `PI18N` (tên, mô tả dịch vụ) theo từng ngôn ngữ.
- `ZALO`, `FANPAGE`: link liên hệ.
