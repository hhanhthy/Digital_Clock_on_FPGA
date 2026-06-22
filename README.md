# Digital_Clock_on_FPGA
youtube: https://www.youtube.com/watch?v=I9IBpSwVAUA
# FPGA Digital Clock & Alarm System

Hệ thống Đồng hồ số và Báo thức được thiết kế và hiện thực hóa trên nền tảng FPGA sử dụng ngôn ngữ Verilog HDL.

## Các tính năng chính
* **Xử lý xung nhịp:** Chia tần số thạch anh MHz thành xung 1Hz chuẩn để đảm bảo độ chính xác thời gian thực.
* **Hiển thị:** Sử dụng kỹ thuật quét đa hợp (Multiplexing) kết hợp tầng lái dòng Transistor BJT để điều khiển hệ thống LED 7 đoạn đôi.
* **Khối điều khiển (FSM):** Tích hợp các chế độ chỉnh giờ/phút hai hướng (Up/Down), Reset hệ thống, và logic báo thức (Alarm) có chức năng nhắc lại sau 5 phút (Snooze).
* **Phân tích phần cứng:** Đánh giá tài nguyên sử dụng (4-input LUTs, DFFs), phân tích giới hạn thời gian (Timing Analysis) và công suất tiêu thụ (Power Analysis).

## Công cụ và Nền tảng
* **Ngôn ngữ:** Verilog HDL
* **Phần cứng:** Kit FPGA kết hợp LED 7 đoạn đôi
* **Phần mềm triển khai:** Microchip Libero SoC
* **Mô phỏng:** ModelSim
