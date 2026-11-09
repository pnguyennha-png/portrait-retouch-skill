---
name: portrait-retouch
description: Chỉnh chân dung và ghép ảnh nhóm bằng pixel ảnh gốc, giữ nhận dạng và kết cấu tự nhiên. Dùng khi cần sửa tỷ lệ đầu-cổ-vai, mép ghép, tóc, màu da hoặc retouch nhẹ trên trình sửa ảnh có lớp và mặt nạ.
license: MIT
---

# Chỉnh chân dung giữ đúng mặt

## Chốt nguồn và giới hạn

- Xác định ảnh gốc, bản cần sửa, thứ tự người và vùng đã được chốt. Khi có nhiều phiên bản, đối chiếu nội dung thực tế; không chọn chỉ theo tên file.
- Với yêu cầu giữ nhận dạng, ưu tiên pixel ảnh gốc. Không tự vẽ lại mặt, thay biểu cảm hay sửa hình dáng mắt, mũi, miệng để làm đẹp. Thay mặt hoặc tạo mặt mới cần người dùng đồng ý cụ thể.
- Đánh giá độ nét, ánh sáng, góc chụp và kích thước sử dụng của nguồn trước khi ghép. Nguồn thiếu dữ liệu cần được nêu rõ, không bịa chi tiết.
- Giữ bản gốc và bản đang sửa riêng. Mọi chỉnh sửa phải có lớp hoặc mặt nạ để sửa lại được. Chỉ sửa vùng được giao; lưu checkpoint trước mỗi thay đổi lớn.

## Căn hình trước khi làm da

1. Dùng ảnh nhóm gốc làm chuẩn vị trí, góc đầu, cổ, bề rộng vai và phối cảnh. So sánh tỷ lệ đầu/vai của chính người đó; không ép mọi người có đầu bằng nhau.
2. Thử dịch chuyển, xoay và thay đổi kích thước đồng đều trước. Không kéo giãn riêng mặt để ép khớp cổ. Nếu góc nguồn không phù hợp, tìm nguồn khác hoặc nêu giới hạn.
3. Ghép theo đường tóc, tai, hàm và cổ. Giữ cấu trúc cổ–vai và để cổ áo che da đúng vị trí. Mặt nạ không được tạo khung chữ nhật, viền đen, bóng kép hay phần tóc bị cụt.
4. Chỉ làm mềm mép đủ để khớp độ nét nguồn. Không dùng blur hoặc bóng tối để che lỗi hình học. Kiểm tra lại cổ trước khi retouch.

## Cân sáng và retouch

- Cân ánh sáng, cân bằng trắng và độ tương phản trong mặt nạ. So mặt với tai, cổ và tay của cùng người, rồi kiểm tra ánh sáng chung của nhóm. Giữ khác biệt màu da tự nhiên.
- Giảm mụn, vết thâm và quầng mắt vừa phải; giữ lỗ chân lông, nếp da và bóng tạo khối. Không làm trắng đồng loạt hoặc bôi mịn toàn mặt.
- Độ rõ phải tương thích với nguồn và các vùng xung quanh. Tránh mắt quá sắc, da nhựa, nhiễu hạt, viền sáng và chi tiết tưởng tượng. Ưu tiên quay lại ảnh nguồn thay vì lặp nhiều lượt làm nét.
- Chỉ chỉnh hoặc tạo kiểu tóc khi yêu cầu cho phép; khóa vùng mặt, ghi rõ phần tóc đã được tạo. Không thay đổi nhận dạng theo kiểu tóc mới.
- Đồng phục, logo và chữ giữ đúng nguồn, vị trí, kích thước và phối cảnh; không tự bịa chữ hoặc phóng to logo.

## Kiểm tra và giao ảnh

Đọc [tiêu chí QC](references/retouch-qc.md) trước khi chốt. Xem toàn bố cục và crop ở 100% pixel ảnh xuất; không dùng ảnh chụp màn hình phóng quá mức để đánh giá chi tiết có thật.

Chỉ báo đạt khi đã xem kết quả: đúng người, tỷ lệ hợp lý, tóc nguyên vẹn, cổ liên tục, màu da tự nhiên, độ rõ đồng đều. Ý kiến người dùng chưa đạt phải được xử lý dù một lượt QC trước đó đã báo đạt.

Xuất PNG sRGB ở kích thước đã thống nhất, một preview nhẹ và bản lớp chỉnh sửa nếu công cụ hỗ trợ. Gọi đúng định dạng thực tế; không đổi đuôi để giả thành PSD. Kiểm tra mở được, kích thước và profile màu. Nếu hứa ngoài mặt nạ không đổi, kiểm tra sai khác pixel trong cùng không gian màu hoặc nói rõ chưa kiểm chứng.

## Làm việc gọn và bảo vệ dữ liệu

Chỉ đọc ảnh nguồn, vùng crop và ghi chú cần thiết. Handoff ngắn gồm nguồn/phiên bản, vùng khóa, phép căn, mặt nạ, thay đổi màu, bản đang xem và lỗi còn lại; không truyền cả lịch sử chat.

Ảnh và dữ liệu riêng chỉ dùng trong phạm vi được phép. Không tự tải lên dịch vụ ngoài, đưa vào kho công khai hoặc nhúng vào tài liệu. Khi chia sẻ skill, chỉ xuất danh sách file văn bản đã rà soát; không kèm ảnh, logo, đường dẫn riêng, ID nguồn, thông tin khách hàng, khóa truy cập hay log.
