# Project-arduino
TÊN ĐỀ TÀI: HỆ THỐNG CHE NẮNG TỰ ĐỘNG CHO NHÀ KÍNH TRỒNG RAU - HOA

## Bản vẽ mô hình
![Screenshot 2024-02-13 093554](https://github.com/Mefuuuu/Project-arduino/assets/133778142/f300f684-07bf-45dc-a0d2-0321786ae6f6)

## Sơ đồ khối
![P1111ture1](https://github.com/Mefuuuu/Project-arduino/assets/133778142/c206716e-1875-4699-9eab-73469b90d4d8)

## Nguyên lý hoạt động
Thông qua các nút nhấn (1) người dùng sẽ thao tác chọn khoảng ánh sáng ( khoảng ánh sáng này đã được thiết đặt từ trước từ người lập trình).Khi  người dùng đã chọn được khoảng ánh sáng mong muốn từ nút nhấn và khởi động chế độ tự động thì quang trở photocell (2) sẽ nhận ánh sáng từ bên ngoài, trả các giá trị điện áp về vi điều khiển để vi điều khiển xác định trời sáng hoặc tối, tiếp theo đó cảm biến ánh sáng BH1750FVI (3) sẽ đọc giá trị ánh sáng hiện tại trong môi trường (trong phòng kính) và đưa giá trị ánh sáng trong vườn hiện tại về vi điều khiển. Vi điều khiển sẽ tiến hành so sánh giá trị ánh sáng trong vườn với khoảng ánh sáng mà người dùng chọn . Sau đó, vi điều khiển sẽ gửi tín hiệu analog ra động cơ (4) (trời sáng) hoặc đèn (5) (trời tối). Đối với động cơ thì khi ánh sáng trong vườn lớn hơn giá trị mong muốn thì động cơ sẽ quay thuận còn khi ánh sáng nhỏ hơn khoảng giá trị mong muốn thì sẽ quay nghịch, đối với đèn thì khi ánh sáng trong phòng thấp hơn thì sẽ tăng mức sáng của đèn lên và ngược lại.

## Linh kiện
- Arduino nano.
- Quang trở
- LCD 2004 tích hợp i2c
- Servo SG90
- LED
- Cảm Biến Cường Độ Ánh Sáng Lux BH1750FVI
- Nút nhấn
- ...

## Sơ đồ nguyên lý mạch
![12cture2](https://github.com/Mefuuuu/Project-arduino/assets/133778142/4a4fc3b7-15f0-4f41-9832-bc767d162532)
