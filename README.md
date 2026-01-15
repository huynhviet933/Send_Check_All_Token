# Send_Check_All_Token

Tham Gia Discor ( Vip ) : https://discord.gg/gKxvTNu5

Tham gia NHóm VIp Với Chi Phí 8u/1thang Lợi ích tham gia nhóm ViP Sẽ được cấp keey sử dụng các tool vip trong discor hỗ trợ Và tham khao Code các tool dự án mà các bạn đề xuất

Gửi Phí tháng vào đây và chụp hình gửi trực tiếp cho tôi tại discor để xác nhận Role VIp ☕ https://huynhviet933.github.io/donate_viet_mmo/ Có thể tặng tôi ít cafe tại đây

![6262733140380028388 (2)](https://github.com/user-attachments/assets/7a468c49-c5a5-41e0-88ad-57d424c3fcb5)


============================================================
       HƯỚNG DẪN SỬ DỤNG DISTRIBUTION TOOL v1.4 (PRO)
============================================================

1. YÊU CẦU HỆ THỐNG
- Đã cài đặt Node.js (phiên bản 16 trở lên).
- Cài đặt các thư viện cần thiết bằng lệnh:
  npm install ethers chalk readline-sync axios

2. CHUẨN BỊ FILE DỮ LIỆU
Trước khi chạy tool, hãy tạo các file .txt cùng thư mục với file pro.js:
- Pk.txt: Dán danh sách Private Key (mỗi dòng 1 key).
- Wallet.txt: Dán danh sách ví nhận (dùng cho chức năng Send).
- config.json: Sẽ tự sinh ra khi chạy tool lần đầu (chứa RPC và Token).

3. CÁC BƯỚC THỰC HIỆN
B1: Chạy Tool bằng lệnh: node pro.js
B2: Nhập License Key khi được yêu cầu (Key sẽ được lưu vào file license.key).
B3: Chọn Mạng lưới (Network) và Token muốn thao tác.

4. GIẢI THÍCH CÁC TÙY CHỌN:
- Option 1 (Send Token): 
  + Nếu Pk.txt có 1 ví, Wallet.txt có nhiều ví -> Tool tự chia tiền từ 1 ví ra nhiều ví.
  + Nếu Pk.txt và Wallet.txt có số lượng bằng nhau -> Tool gửi 1 đối 1.
  + Nếu để trống Amount -> Tool tự tính toán chia ĐỀU toàn bộ số dư.
- Option 2 (Check Balance):
  + Kiểm tra số dư toàn bộ ví trong Pk.txt.
  + Kết quả sẽ hiển thị trên màn hình và xuất ra file balance.txt.
- Option 3 (Sweep Token):
  + Gom toàn bộ tiền/token từ danh sách ví trong Pk.txt về 1 địa chỉ ví duy nhất.
  + Nếu để trống Amount -> Tool sẽ gom SẠCH (Sweep All).

5. QUẢN LÝ MẠNG VÀ TOKEN:
- Bạn có thể chọn "Add New Network" để thêm mạng tùy chỉnh (L2, Testnet...).
- Bạn có thể chọn "Add New Token" để thêm Contract Address của các token khác.

LƯU Ý QUAN TRỌNG:
- Luôn đảm bảo ví có đủ phí gas (ETH/BNB...) để thực hiện giao dịch.
- Bảo mật file Pk.txt tuyệt đối, không chia sẻ cho người khác.
- Nếu tool báo License Invalid, hãy liên hệ admin để kích hoạt HWID của bạn.
============================================================
