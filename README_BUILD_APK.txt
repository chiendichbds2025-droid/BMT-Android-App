BMT ANDROID APP v1.0

Mục tiêu:
- APK cài trực tiếp Android.
- GPS hiển thị vị trí hiện tại.
- Khoảng cách tới nhãn, xếp gần -> xa.
- Tìm kiếm ưu tiên HC cũ.
- Lọc Phường/Xã -> Đường -> Thôn/Buôn.
- Cập nhật dữ liệu bằng file JSON, không cần cài lại app.
- 2.291 nhãn seed hiện tại.

Build APK bằng GitHub Actions:
1. Đưa toàn bộ thư mục project này lên một GitHub repository.
2. Vào tab Actions.
3. Chạy workflow "Build Android APK".
4. Mở lần chạy thành công.
5. Tải artifact "BMT-Map-debug-apk".
6. Trong artifact có app-debug.apk để cài Android.

Sau khi cài app:
1. Mở BMT Map.
2. Cho phép quyền vị trí.
3. Bấm nút ◎ để bật/tắt GPS.
4. Mở Lọc để tìm kiếm/lọc dữ liệu.
5. Cập nhật dữ liệu: Lọc -> Cập nhật dữ liệu -> chọn JSON -> Nhập / ghi đè update.
