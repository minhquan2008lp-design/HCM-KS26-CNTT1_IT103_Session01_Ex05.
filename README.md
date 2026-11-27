1. Bước 1: Ba điểm hạn chế của sơ đồ cũ
1. Không kiểm tra trạng thái đơn hàng: Cho phép đổi địa chỉ ngay cả khi tài xế đã lấy hàng.
2. Thiếu lối thoát: Không có nút Hủy hoặc Quay lại khi khách đang nhập địa chỉ mới.
3. Nhánh báo lỗi bị cụt: Khi địa chỉ vượt quá 5 km, chỉ hiện thông báo lỗi và không cho khách nhập lại.
2. Bước 2: User Flow hoàn chỉnh
Bạn có thể dựa vào sơ đồ dưới đây để vẽ lại trên FigJam.
USER FLOW – ĐỔI ĐỊA CHỈ GIAO HÀNG
BẮT ĐẦU

Xem đơn hàng

Kiểm tra trạng thái đơn hàng

Tài xế đã lấy hàng chưa?


Rồi
Khóa thao tác đổi địa chỉ

Hướng dẫn liên hệ tài xế / tổng đài
KẾT THÚC


Chưa
Cho phép đổi địa chỉ

Nhập địa chỉ mới

Khoảng cách ≤ 5 km?





Không
Thông báo địa chỉ vượt quá 5 km
Quay lại Nhập địa chỉ mới


Có
Cập nhật địa chỉ

Cập nhật thành công

KẾT THÚC




Lối thoát bổ sung

Tại màn hình Nhập địa chỉ mới → Hủy thao tác → Giữ nguyên địa chỉ cũ → Kết thúc.


Lưu ý khi vẽ FigJam:
Ký hiệu	Ý nghĩa
Oval	Bắt đầu / Kết thúc
Hình chữ nhật	Thao tác / Màn hình
Hình thoi	Điều kiện kiểm tra
Mũi tên	Hướng di chuyển

Nhớ ghi nhãn Rồi/Chưa, Có/Không trên các mũi tên rẽ nhánh.
3. Bước 3: Viết thông báo lỗi (≤ 80 ký tự)
Địa chỉ cách quán 7,2 km, vượt bán kính giao hàng 5 km. Vui lòng chọn lại địa chỉ trong phạm vi cho phép.




Số ký tự: 112 (bao gồm khoảng trắng và dấu câu).
Vượt giới hạn

Bản rút gọn đạt yêu cầu:
Địa chỉ cách quán 7,2 km, vượt giới hạn 5 km. Vui lòng chọn lại!




Số ký tự: 66 (bao gồm khoảng trắng và dấu câu).
Đạt yêu cầu

4. Bước 4: Ghi chú Heuristic
- Heuristic #3 – Lối thoát: Có nút Hủy thao tác để giữ địa chỉ cũ.
- Heuristic #5 – Phòng ngừa lỗi: Kiểm tra trạng thái đơn trước khi cho phép đổi địa chỉ.
- Heuristic #9 – Thông báo lỗi: Nêu rõ khoảng cách, giới hạn và hướng xử lý tiếp theo.