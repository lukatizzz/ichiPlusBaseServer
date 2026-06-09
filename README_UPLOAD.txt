CÁCH UPLOAD LÊN SERVER (FileZilla)
================================

1. Trên FileZilla, điều hướng đến thư mục ichiplus/sever/ trên server
   (thư mục tương ứng với https://t4.zyyx.vn/ichiplus/sever/)

2. Upload TOÀN BỘ nội dung trong thư mục này:
   - index.html          → Trang test link (hiện khi vào /ichiplus/sever/)
   - fallback.html       → Trang fallback (tham chiếu)
   - password/           → Thư mục (bên trong có index.html)
   - baseQRInfo/         → Thư mục (bên trong có index.html)
   - baseRentalQRInfo/   → Thư mục (bên trong có index.html)
   - QRreader/           → Thư mục (bên trong có index.html)
   - extWebLink/         → Thư mục (bên trong có index.html)
   - extAppLink/         → Thư mục (bên trong có index.html)
   - RFIDreader/         → Thư mục (bên trong có index.html)
   - Beacon/             → Thư mục (bên trong có index.html)
   - reservations/       → Thư mục (bên trong có index.html)

3. Kết quả:
   - https://t4.zyyx.vn/ichiplus/sever/              → Trang test
   - https://t4.zyyx.vn/ichiplus/sever/baseQRInfo?... → Trang "Mở trong app" (không còn 404)
