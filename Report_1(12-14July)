# Báo cáo tuần 1 (12/7/2023-14/7/2023)
## 1.SOC platform VCS)(https://viettelcybersecurity.com/vi/vcs-giai-phap-cho-chinh-phu-va-doanh-nghiep-lon-vi/)
Giải pháp tích hợp nhiều thành phần, hệ thống An toàn thông tin để thực hiện giám sát vận hành toàn diện
-	Bảo mật trên lớp endpoint, network và các hệ thống khác
-	Thu thập log, quản lý tập trung và đưa ra cảnh báo
-	Tự động hóa phân tích, điều tra, truy vết dựa trên kịch bản có sẵn
-	Tùy chỉnh quy trình và kịch bản xử lý
-	Tích hợp trên một nền tảng duy nhất

Những đặc điểm chính

Đăng nhập
-	Đăng nhập bảo mật xác thực hai lớp
-	Hỗ trợ tiêu chuẩn SSO (single sign on), SLO (single log out)
-	Cho phép đăng nhập tập trung

Quản lý khách hang
-	Hỗ trợ xác thực, giới hạn tốc độ kết nối, dữ liệu

Quản lý người dung
Giám sát tập trung, theo dõi, phân tích log
-	Theo dõi trạng thái các agent
-	Cung cấp giao diện giám sát sự cố

Điều tra sự cố
-	Tìm kiếm event để điều tra khi có sự cố
-	Cung cấp tính năng cô lập máy tính, chặn tiến trình
-	Cung cấp công cụ hiển thị dữ liệu (visualize)

Dashboard quản lý giám sát hệ thống

Báo cáo
-	Cung cấp báo cáo KPI, cam kết chất lượng (SLI - Service Level Indicator)
-	Gửi báo cáo tự động định kỳ cho khách hàng
-	Tùy chỉnh nội dung báo cáo

Triển khai linh hoạt
-	On-premise, Cloud, Hybrid

Thành phần hệ thống:
-	IAM (Identity Access Management): Quản lí định danh và truy cập
-	Main Portal: Quản lí người dung, liên kết với các thành phần trong hệ thống
-	Các giải pháp thành phần
    - Endpoint Detection and Response (VCS-aJiant)
    - Network Security Monitoring (VCS-NSM)
    - Security Information & event management (VCS-CyM)
    - Security Orchestration, Automation & Response (VCS-CyCir)
    - Hỗ trợ hệ thống đa khách hàng (multi-tenant)
---
VCS Network security Monitoring
docs:(https://viettelcybersecurity.com/wp-content/uploads/2021/10/VCS-NSM.pdf)

Giám sát lưu lượng mạng theo thời gian thực và đưa ra cảnh báo về các cuộc tấn công mạng dựa trên phân tích nội dung của các gói tin ra vào hệ thống. Dựa vào các bộ luật đặt sẵn để phát hiện những hành vi bất thường trên lớp mạng (vd: Network Scan, Trojan Activities, Shellcode Detect, Web Application Attack, Suspicious Login,..). Từ nội dung các gói tin phát hiện những cách tấn công phổ biến sử dụng các dấu hiệu biết trước (signature). Ngoài ra, Network traffic cũng được lưu lại để các quản trị viên có thể phân tích sâu hơn.

---

Security Information & event management (VCS-CyM)
docs:(https://viettelcybersecurity.com/wp-content/uploads/2021/10/VCS-CyM.pdf)

SIEM - Công cụ chuẩn hoá thu thập, lưu trữ và phân tích tương quan toàn bộ log, các sự kiện xẩy ra trong hệ thống. Có công cụ tìm kiếm, ngôn ngữ tìm kiếm và trực quan hoá dữ liệu để đễ dàng hơn trong việc theo dõi và ohaan tích sự cố. Cung cấp hệ thống quản lý ticket và workflow với khả năng lưu trữ, truy vết lịch sử, quản lý vòng đời sự cố. Có sẵn bộ chuẩn hoá của hơn 100 loaị ứng dụng thiết bị phổ biến.

---

Endpoint Dectection and Response
docs:(https://viettelcybersecurity.com/wp-content/uploads/2023/06/Datasheet-VCS-aJiant-2023-VI.pdf)

Giải pháp bảo vệ thiét bị đầu cuối. Giám sát hành vi bất thường theo chuẩn MITRE ATT&CK. Thiết lập chính sách an toàn thông tin. Hệ thống giám sát ở tầng thấp nhất của hệ thống (kernel mode). Sử dụng công nghe filter driver để giám sát các hành vi liên quan đến File, Process, Memory, Registry, Network và đẩy log về backend phân tích tập trung. Khi phát hiện tấn công thì lưu lại các dấu hiệu bất thường và cung cấp các công cụ gỡ bỏ mã độc.

---

Security Orchestration, Automation & Response (VCS-CyCir)
doc: (https://viettelcybersecurity.com/wp-content/uploads/2021/07/Security-Orchestration-Automation-Response.pdf)

SOAR - Security Orchestration, Automation and Response. Giải pháp điều phối, tự động hóa phản ứng an ninh thông tin tập trung. Cung cấp sẵn nhiều công cụ và kịch bản (playbook bằng ngôn ngữ python) phổ biến cùng với khả năng tuỳ biến playbook để phù hợp với các công nghệ bảo mật và nhu cầu của tổ chức. Workflow engine giúp tự động hoá việc thực hiện các playbook. Các bản ghi hệ thống được lưu lại trong quá trình vận hành để các chuyên gia có cái nhìn tổng thể nhất về sự cố. Hỗ trợ các công cụ trích xuất ra các báo cáo và dashboard chuyên biệt cho cả 3 lớp người dùng của tổ chức: Chuyên gia phân tích, SOC Manager và Giám đốc An ninh thông tin (CISO).

---

## Nghiên cứu một số giải pháp soc platform open source

- opensource EDR solution : Wazuh, Security onion
- opensource network monitoring: OSSEC HIDS, Security Onion
- opensource Security Information & event management (SIEM): Wazuh, Security Onion
- open source Security Orchestration, Automation & Response: Wazuh, Security Onion

**Wazuh documentation**: (https://readthedocs.org/projects/snaow-docs/downloads/pdf/latest/)

**Wazuh và Security Onion** đã được tịch hợp đầy đủ với ELK stack, cung cấp công cụ tìm kiếm và công cụ trực quan hóa dữ liệu grafana (https://grafana.com/docs/grafana-cloud/data-configuration/metrics/prometheus-config-examples/wazuh-inc-wazuh-kibana/)

**Security Onion documentation**: (https://securityonion.net/security)

**wazuh** host-based intrution detection

**security onion** network security monitoring platform
