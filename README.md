MÔ TẢ CHỨC NĂNG & HƯỚNG DẪN SỬ DỤNG 
ỨNG DỤNG CHẤM BÀI KIỂM TRA By TVB CVA-HD-CM (BẢN v25)

Ứng dụng Chấm Bài Kiểm Tra By TVB CVA-HD-CM (v25) là công cụ chấm thi tự động bằng AI trên điện thoại và máy tính, hỗ trợ chấm đồng thời Trắc nghiệm (ABCD, Đúng/Sai, Trả lời ngắn) và Tự luận từ ảnh chụp hoặc file PDF trong vài giây/bài.
1. Điểm nổi bật của phiên bản v25
•	Nạp đáp án Offline (0 tốn lượt API):Tự động tách bảng đáp án Trắc nghiệm ngang/dọc và biểu điểm Tự luận trực tiếp từ file Word (.docx) và .pdf.
•	Tự động định tuyến API: Tự chọn mô hình miễn phí có hạn mức cao nhất (1500 lượt/ngày), tự động né các model giới hạn 20 lượt/ngày và tự chuyển luồng khi máy chủ quá tải.
•	Độ nét 1024px & Bộ nhớ đệm: Tối ưu nhận diện chữ viết tay và vết khoanh trắc nghiệm mà không tốn thêm token; chấm lại cùng 1 bài không mất lượt API.
•	Quản lý điểm đồng bộ: Tự khớp Họ tên/SBD/Mã phách với danh sách lớp mẫu, hỗ trợ gộp điểm từ nhiều giáo viên và xuất file Excel đầy đủ cột điểm từng câu.
3. Bảng hướng dẫn sử dụng các nút chức năng
⚙️ Khu vực 1: Đáp án & Cấu hình AI
Nút chức năng	Tác dụng & Cách dùng
👉 Lấy API Key miễn phí	Mở trang Google AI Studio để tạo mã API Key cá nhân.
👁️ Hiện / 🙈 Ẩn	Hiện hoặc ẩn chuỗi ký tự API Key đang nhập trong ô.
🔄 Quét & Chọn Gói Tốt Nhất	Kiểm tra thực tế tài khoản API và tự động chọn model sống có hạn mức cao nhất (1500 lượt/ngày).
💾 Lưu API / 🗑️ Xóa API	Lưu cố định API Key trên trình duyệt máy đang dùng hoặc xóa sạch khỏi bộ nhớ máy (nếu không bấm Lưu, Key tự xóa khi đóng tab).
Đặt lại 0	Đặt lại bộ đếm số lượt gọi API trong ngày về 0 và mở khóa lại các model tạm khóa.
⚡ Hạn mức cao nhất / 🎯 Cân bằng	Chọn ưu tiên model siêu tốc 1500 lượt/ngày (flash-lite) hoặc model đọc chữ viết tay chuẩn xác cao (flash).
📂 Chọn file Đáp án (.docx / .pdf)	Tải file Hướng dẫn chấm lên để ứng dụng tự động điền đáp án ABCD, Đúng/Sai, Trả lời ngắn và biểu điểm Tự luận.
🗑️ Xóa trắng toàn bộ Đáp án	Xóa sạch đáp án và biểu điểm của đề cũ để nhập đề kiểm tra mới.
📚 Cả TN & TL / ☑️ Chỉ TN / ✍️ Chỉ TL	Chuyển chế độ chấm theo cấu trúc đề (Ứng dụng tự nhận diện khi nạp file đáp án, hoặc bấm chọn thủ công).
👁️ Hiện tất cả các phần đang ẩn	Mở lại toàn bộ các khung nhập đáp án (Phần I, II, III, IV) đã được tự động thu gọn để sửa thủ công.
🧠 Linh hoạt / 📏 Sát biểu điểm	Linh hoạt: Học sinh trình bày cách giải khác nhưng đúng bản chất vẫn đạt điểm tối đa. Sát biểu điểm: Chấm khớp từng ý theo HDC.
📷 Khu vực 2: Đưa bài làm Học sinh lên chấm
Nút chức năng	Tác dụng & Cách dùng
📄 Đề A4 / 📝 Giấy thi	Chọn Đề A4 nếu học sinh khoanh/điền trực tiếp trên đề; chọn Giấy thi nếu học sinh viết tay đáp án 1A, 2B... ra giấy.
📷 Chụp trang (Camera ĐT)	Mở camera sau của điện thoại để chụp liên tiếp từng trang bài làm của 1 học sinh.
🖼️ Chọn nhiều ảnh	Chọn một lúc nhiều trang ảnh bài làm của 1 học sinh đã chụp sẵn trong thư viện máy.
📄 Nạp file PDF bài làm	Tải lên file PDF chứa các trang bài làm của 1 học sinh.
📥 Ghép các trang & Tải 1 file ảnh	Ghép toàn bộ các trang ảnh của học sinh đang chấm thành 1 file ảnh dài duy nhất kèm tiêu đề tên HS/Mã phách để lưu minh chứng.
🗑️ Xóa tất cả ảnh	Xóa các trang ảnh hiện tại trong túi bài làm để chụp hoặc chọn lại.
⚡ Bắt đầu chấm siêu tốc	Gửi toàn bộ các trang trong túi bài làm để AI chấm và trả kết quả.
📊 Khu vực 3: Kiểm tra & Lưu điểm
Nút chức năng / Thao tác	Tác dụng & Cách dùng
Chạm vào từng ô câu Trắc nghiệm	Đảo trạng thái Đúng (Xanh ✓) ↔ Sai (Đỏ) nếu muốn chỉnh sửa thủ công; tổng điểm tự động cộng lại ngay lập tức.
Ô điểm Tự luận / + Thêm câu	Sửa trực tiếp điểm từng câu tự luận, thêm câu mới hoặc bấm ✕ để xóa câu thừa.
💾 Lưu điểm vào Danh sách lớp	Lưu kết quả học sinh vào bảng điểm tổng hợp (nếu trùng tên/SBD/Mã phách đã có, ứng dụng sẽ hỏi để tự động ghép điểm).
🗑️ Không lưu — Xóa tất cả ảnh	Hủy kết quả vừa chấm và xóa túi ảnh hiện tại để chụp lại bài làm.
📁 Khu vực 4: Bảng điểm tổng hợp & Xuất dữ liệu
Nút chức năng	Tác dụng & Cách dùng
📷 Chụp ảnh DS mẫu / 📂 Tải File DS	Nạp danh sách học sinh của lớp (từ Excel, Word, PDF hoặc chụp ảnh danh sách giấy) để AI tự động sửa đúng chính tả Họ tên, điền SBD/Lớp và giữ đúng thứ tự STT.
🔗 Gộp file Excel từ GV khác	Nạp file Excel điểm từ máy giáo viên khác (ví dụ: người chấm TN, người chấm TL hoặc chia câu TL) để tự động ghép thành điểm tổng hợp cho từng học sinh.
📤 Xuất / Chia sẻ File Excel (.xlsx)	Xuất file Excel đầy đủ các cột: STT, SBD, Mã phách, Mã đề, Họ tên, Lớp, Điểm TN, Điểm từng câu TL và Tổng cộng.
📋 Copy Đầy đủ / 📋 Copy Rút gọn	Sao chép toàn bộ bảng điểm vào bộ nhớ tạm để dán (Ctrl + V) trực tiếp vào file Excel hoặc Google Sheets sổ điểm điện tử mà không bị lệch dòng.
🗑️ Xóa tất cả để chấm lớp mới	Xóa toàn bộ danh sách điểm đã lưu của lớp hiện tại để chuyển sang chấm lớp khác.
4. Quy trình 4 bước sử dụng nhanh
Bước 1 — Cấu hình lần đầu (Mục 1): Dán API Key → bấm 🔄 Quét & Chọn Gói Tốt Nhất → bấm 💾 Lưu API.
Bước 2 — Nạp Đáp án & Danh sách lớp: Bấm 📂 Chọn file Đáp án (.docx / .pdf) ở Mục 1 để nạp hướng dẫn chấm; bấm 📂 Tải File / Ảnh ở Mục 4 để nạp danh sách học sinh của lớp (nếu có).
Bước 3 — Chấm từng học sinh (Mục 2 & 3): Bấm 📷 Chụp trang (hoặc 🖼️ Chọn nhiều ảnh) đủ các trang của 1 học sinh → bấm ⚡ Bắt đầu chấm siêu tốc → kiểm tra nhanh điểm và bấm 💾 Lưu điểm vào Danh sách lớp.
Bước 4 — Xuất bảng điểm (Mục 4): Sau khi chấm xong cả lớp, bấm 📤 Xuất / Chia sẻ File Excel hoặc 📋 Copy để dán vào sổ điểm.
