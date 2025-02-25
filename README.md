# Xây dựng Sinkhole để xử lý mã độc APT

Đây là tài liệu bài trình bày **"Xây dựng Sinkhole để xử lý mã độc APT"**  
tại **Tradahacking 2017**, do **Trần Minh Quảng** (Công ty An ninh mạng Viettel) thực hiện.

---

## 📌 Tổng quan
Bài trình bày cung cấp cái nhìn chi tiết về **cách xây dựng hệ thống Sinkhole để phát hiện và xử lý mã độc APT**, bao gồm:
- **Tổng quan về tấn công APT** và tác động đến các tổ chức tại Việt Nam.
- **Phân tích phương pháp giám sát và phát hiện mã độc APT** trên mạng và endpoint.
- **Xây dựng máy chủ Sinkhole**: Chuyển hướng kết nối độc hại, giả lập máy chủ điều khiển C&C, định danh máy tính bị nhiễm.
- **Nghiên cứu điển hình về mã độc PlugX**: Cấu trúc giao tiếp, các lệnh điều khiển và cách khai thác Sinkhole để xử lý.

---

## 📂 Tệp tin trong repo
- 📄 **`sinkhole_apt.pdf`** – Slide bài trình bày tại Tradahacking 2017.

---

## 🚀 Điểm nổi bật
- **APT là mối đe dọa lớn tại Việt Nam**, nhắm vào chính phủ, doanh nghiệp lớn với mã độc có khả năng ẩn mình lâu dài.
- **Sinkhole giúp phát hiện máy tính bị nhiễm ngay cả khi bị NAT**, cho phép kiểm soát tốt hơn so với các phương pháp giám sát truyền thống.
- **Phân tích thực tế về mã độc PlugX**, một trong những công cụ tấn công phổ biến của các nhóm APT.
- **Kết hợp nhiều phương pháp như phân tích traffic, reverse engineering mã độc để tối ưu hiệu quả phát hiện và xử lý.**

---

## 🛡 Giải pháp phòng chống
- **Triển khai hệ thống Sinkhole** để theo dõi và định danh máy bị nhiễm.
- **Giám sát DNS và lưu lượng mạng** để phát hiện kết nối đến máy chủ C&C của mã độc.
- **Phân tích hành vi mã độc** thông qua dữ liệu thu thập được từ Sinkhole.
- **Hợp tác giữa các tổ chức, ISP để xử lý triệt để các mối đe dọa từ APT**.

---

## 📢 Về tác giả
- **Trần Minh Quảng** - Chuyên gia An ninh mạng, Viettel Cyber Security  
  📍 **Chuyên môn**: Phân tích mã độc, điều tra APT, xây dựng hệ thống giám sát an ninh mạng  
  ✉️ Liên hệ: [Email của bạn] | [Viettel Cyber Security](https://viettelcybersecurity.com)

---

## ⚠️ Điều khoản
Tài liệu này chỉ nhằm mục đích **nghiên cứu và giáo dục**. Tác giả và Viettel Cyber Security không chịu trách nhiệm về bất kỳ hành vi sử dụng sai mục đích nào.

---

🔍 **Tăng cường khả năng phòng thủ trước các cuộc tấn công APT với Sinkhole!**
