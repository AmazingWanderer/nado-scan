# nado-scan

Trang quét QR Thẻ thi đấu cho Bàn trọng tài Infinity Nado.

- Một trang tĩnh (`index.html`) + thư viện `html5-qrcode` 2.3.8 (`html5-qrcode.min.js`).
- Camera được xử lý ngay trên máy; trang không gửi ảnh, video hay dữ liệu lên máy chủ nào.
- Trang không nhận token đăng nhập, không gọi máy chủ, không ghi Sheet. Nó chỉ trả mã tuyển thủ vừa quét
  về Bàn trọng tài (qua `postMessage`, hoặc qua URL quay về khi trình duyệt không giữ quan hệ cửa sổ).
- Danh sách khung được nhận mã (`OPENERS`) và URL được quay về (`RETURNS`) nằm ở khối CẤU HÌNH đầu phần mã trong `index.html`.

Không có dữ liệu tuyển thủ nào trong repo này.
