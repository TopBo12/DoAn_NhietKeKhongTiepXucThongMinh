# DoAn_NhietKeKhongTiepXucThongMinh

## 1. Tên đề tài
Nhiệt kế không tiếp xúc thông minh

## 2. Mô tả ngắn gọn
Đề tài nghiên cứu và xây dựng hệ thống đo nhiệt độ cơ thể
không tiếp xúc sử dụng cảm biến hồng ngoại MLX90614 kết hợp
với vi điều khiển ESP32-CAM. Hệ thống giúp đo nhiệt độ nhanh,
an toàn, hạn chế tiếp xúc trực tiếp và có khả năng mở rộng
kết nối IoT phục vụ giám sát từ xa.

## 3. Phần mềm và công cụ sử dụng
- Arduino IDE / Visual studio code (platformio): lập trình cho ESP32-CAM  
- Thư viện Arduino: ESP32 Camera, MLX90614, QR Code, LCD
- Altium Designer: thiết kế sơ đồ nguyên lý và PCB  
- ThingSpeak: lưu trữ và hiển thị dữ liệu đo

## 4. Cách chạy code
1. Cài đặt Arduino IDE
2. Cài đặt board ESP32 cho Arduino IDE
3. Kết nối ESP32-CAM với máy tính
4. Mở chương trình trong thư mục `DA2_1`
5. Cấu hình thông tin WiFi (SSID, Password) trong code
6. Chọn đúng board ESP32-CAM và cổng COM
7. Nạp chương trình vào ESP32-CAM
8. Quan sát dữ liệu nhiệt độ qua màn hình LCD hoặc nền tảng IoT

## 5. Nội dung các thư mục

- `DA2_1`  
  Chứa toàn bộ mã nguồn chương trình điều khiển hệ thống đo nhiệt độ
  không tiếp xúc sử dụng ESP32-CAM, bao gồm đọc dữ liệu từ cảm biến
  MLX90614, quét QR Code, hiển thị LCD và gửi dữ liệu lên ThingSpeak.

- `Báo Cáo Đồ Án II`  
  Chứa file báo cáo đồ án “Nhiệt kế không tiếp xúc thông minh” định dạng Word,
  trình bày đầy đủ cơ sở lý thuyết, thiết kế hệ thống, thực nghiệm và đánh giá kết quả.

- `DOAN2`  
  Chứa sơ đồ nguyên lý (Schematic), layout PCB và các file thiết kế mạch
  phục vụ chế tạo phần cứng của hệ thống.
## 6.Note
1.Thay đổi ssid = "name wifi" và password = "pass wifi".
2.Tạo QR code ở dạng text với dạng text là :{"id":"mã id","name": "Tên người dùng","channel":channel trên thingspeak ,"key": "mã API key của channel trên thingspeak"}.


