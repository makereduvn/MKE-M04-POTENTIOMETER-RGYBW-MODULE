# Mạch biến trở MKE-M04 Potentiometer RGYBW Module

MKE-M04 Potentiometer RGYBW Module là mạch biến trở cho phép tạo ra giá trị điện áp Analog tuyến tính tương ứng với góc xoay của trục biến trở, giúp người dùng dễ dàng ghi nhận và xử lý tín hiệu một cách chính xác. Sản phẩm thường được sử dụng trong các ứng dụng điều khiển tăng/giảm giá trị như điều chỉnh tốc độ, độ sáng, âm lượng, cũng như trong các mô hình robot, dự án STEM, đồ án học tập và thực hành điện tử.

Biến trở được trang bị nắp chụp nhiều màu sắc giúp dễ dàng phân biệt khi lắp đặt và sử dụng. Mạch có 5 phiên bản màu gồm: Đỏ, Xanh lá, Vàng, Xanh dương và Trắng, đáp ứng đa dạng nhu cầu ứng dụng.

Mạch biến trở MKE-M04 Potentiometer RGYBW Module hỗ trợ điện áp điều khiển 3.3V và 5VDC, cho phép kết nối trực tiếp và an toàn với hầu hết các bo mạch điều khiển phổ biến hiện nay như Arduino, Raspberry Pi, Jetson Nano, Micro:bit và nhiều nền tảng khác. Sản phẩm đi kèm cáp kết nối 3P XH2.54 – Dupont, đảm bảo kết nối chắc chắn, ổn định và thuận tiện trong quá trình sử dụng.

## Thông số kỹ thuật
- Điện áp cấp nguồn: 5VDC
- Chuẩn tín hiệu điều khiển: Analog
- Điện áp giao tiếp: 0~3.3VDC
- Màu sắc nắp chụp biến trở: Đỏ, Xanh lá, Vàng, Xanh dương, Trắng
- Khả năng tương thích:
  - Arduino
  - Raspberry Pi
  - Jetson Nano
  - Micro:bit
  - Và các board điều khiển 3.3/5VDC khác
- Thiết kế mạch:
  - Ổn định, chống nhiễu
  - Phù hợp cho ứng dụng học tập và thực tế
- Đi kèm cáp kết nối: 3P XH2.54–Dupont

## Các chân tín hiệu
<table><thead>
  <tr>
    <th>MKE-M04</th>
    <th>Ghi chú</th>
  </tr></thead>
<tbody>
  <tr>
    <td>GND</td>
    <td>Chân cấp nguồn âm 0VDC</td>
  </tr>
  <tr>
    <td>5V</td>
    <td>Chân cấp nguồn dương 5VDC</td>
  </tr>
  <tr>
    <td>SIG</td>
    <td>Chân tín hiệu Analog Out</td>
  </tr>
</tbody>
</table>

## Hướng dẫn sử dụng
### Hướng dẫn kết nối
- Cấp nguồn 5VDC cho mạch qua hai chân GND và 5V.
- Nhận tín hiệu từ biến trở qua chân tín hiệu SIG.
<table><thead>
  <tr>
    <th>SIG (Analog Out)</th>
    <th>Trạng thái</th>
  </tr></thead>
<tbody>
  <tr>
    <td>Max</td>
    <td>3.3VDC</td>
  </tr>
  <tr>
    <td>Min</td>
    <td>0VDC</td>
  </tr>
</tbody>
</table>

### Hướng dẫn sử dụng với Arduino Uno / Vietduino Uno / ESP32
- Trong **Tools / Library Manager**, tìm và cài đặt bộ thư viện tổng hợp **"MKE_ONE" by MakerEdu.vn**
- Mở chương trình mẫu **"MKE_M04_Potentiometer_Serial_XXX"** tại **File / Examples / MAKEREDU / Module / MKE_M04_Potentiometer**
- Cấu hình board mạch tương ứng là **Arduino Uno / ESP32**, chọn đúng cổng **COM Port** của mạch và nhấn **Upload** để nạp chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân SIG của module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

### Hướng dẫn lập trình với Micro:bit (kéo thả khối)

- Khởi động [Microsoft MakeCode](https://makecode.microbit.org/) và **Import** chương trình theo đường link sau: `https://github.com/makereduvn/mke_m04_potentiometer_microbit/`
- Kết nối mạch Micro:bit và **Download** chương trình.
- Cấp nguồn 5VDC cho mạch, kết nối chân SIG của module với chân điều khiển được khai báo trong chương trình.
- Xem kết quả mạch hoạt động theo chương trình đã nạp.

Nếu bắt đầu tự án mới cần cài đặt Extension **MKE_ONE_MICROBIT** trên [Microsoft MakeCode](https://makecode.microbit.org/) theo [hướng dẫn tại đây](https://github.com/makereduvn/MKE_ONE_MICROBIT). Sau khi cài đặt thành công, các khối lệnh của Extension **MKE_ONE_MICROBIT** sẽ xuất hiện trong danh sách block và sẵn sàng để sử dụng.

## Kích thước sản phẩm
![MKE-M04 Potentiometer](/extras/MKE-M04_1.jpg)

## Hình ảnh sản phẩm
![MKE-M04 Potentiometer](/extras/MKE-M04_2.png)
![MKE-M04 Potentiometer](/extras/MKE-M04_3.png)





