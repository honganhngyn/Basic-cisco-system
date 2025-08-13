# Xây Dựng Hệ Thống Mạng Cho Doanh Nghiệp (Cisco Packet Tracer)

## Giới thiệu
Dự án này mô phỏng **hệ thống mạng cho một doanh nghiệp** với trụ sở chính và một chi nhánh phụ, được thiết kế và cấu hình trên **Cisco Packet Tracer**.

Mục tiêu:
- Triển khai mạng LAN, VLAN, DMZ, và Wi-Fi nội bộ.
- Cấu hình DHCP, DNS, Web Server, Mail Server, FTP Server.
- Thiết lập Access Control List (ACL) để đảm bảo tính bảo mật, đặc biệt cách ly phòng kế toán với các mạng khác.
- Kết nối giữa trụ sở chính và chi nhánh phụ qua định tuyến.

## Nội dung
## Yêu cầu phần mềm
- **Cisco Packet Tracer** (phiên bản 8.2 trở lên để đảm bảo tương thích với file `.pkt`)
- Hệ điều hành: Windows, macOS, hoặc Linux đều được hỗ trợ bởi Cisco Packet Tracer.

## Cách sử dụng
1. **Tải Cisco Packet Tracer** từ trang chính thức của Cisco Networking Academy:  
   [https://www.netacad.com/courses/packet-tracer](https://www.netacad.com/courses/packet-tracer)

2. **Clone hoặc tải repo về máy**:
   ```bash
   git clone https://github.com/<username>/<repo-name>.git
   cd <repo-name>

3. **Khám phá mô hình**
   	- Xem sơ đồ kết nối tổng thể
   	- Mở từng thiết bị (router, switch, PC, server) để xem cấu hình
   	- Dùng công cụ Simulation Mode để kiểm tra luồng dữ liệu và bảo mật ACL

4. **Kiểm thử**
   	- Ping và truy cập dịch vụ giữa các VLAN (theo chính sách bảo mật)
   	- Truy cập Web/Mail/FTP server từ mạng nội bộ
   	- Chặn truy cập từ ngoài vào phòng kế toán (theo ACL)
   	- Kết nối giữa chi nhánh và trụ sở chính

![Mô hình mạng](https://github.com/honganhngyn/Basic-cisco-system/blob/main/mohinhmang.png)
