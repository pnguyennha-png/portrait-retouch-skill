# Kiểm tra chất lượng độc lập

Người kiểm tra phải xem ảnh thật cùng nguồn đối chiếu, không chỉ đọc mô tả người sửa. Ghi rõ ảnh đã xem và tỷ lệ hiển thị. Chưa xem ảnh thì chưa được báo QC đạt.

## Ba lượt xem

1. **Toàn ảnh ở kích thước sử dụng:** đúng thứ tự người, tỷ lệ đầu/vai theo ảnh gốc, hướng sáng thống nhất, đầu không nổi rời khỏi thân. Người gần máy có thể lớn hơn; không lấy một người làm kích thước chung.
2. **100% pixel bản xuất:** soi tóc, hai tai, hai bên cổ, dưới cằm, đỉnh và đáy cổ áo; tìm viền đen/sáng, mép răng cưa, miếng vá chữ nhật, màu đứt đoạn và cổ áo chồng sai.
3. **So với nguồn:** đúng hình dáng mặt, biểu cảm, chi tiết mắt–mũi–miệng; retouch không làm mất nhận dạng. So độ sáng mặt–tai–cổ–tay của từng người, giữ sắc da tự nhiên.

## Dấu hiệu lỗi và hướng sửa

| Dấu hiệu | Kiểm tra và sửa |
| --- | --- |
| Đầu trông lạc quẻ | Đối chiếu tỷ lệ với ảnh nhóm gốc, góc chụp, độ nghiêng, vị trí cổ, nhiệt độ màu và tương phản trước khi đổi cỡ. |
| Đường cắt ở cổ | Kiểm tra phép căn và cổ áo che da. Sửa mặt nạ theo giải phẫu; không vẽ viền đen hoặc tăng blur để che đường cắt. |
| Tóc mất mảng hoặc viền xanh | Quay lại mặt nạ và nguồn gốc; phục hồi sợi tóc thật. Chỉ khử màu nền ở mép cần thiết. |
| Da mặt sáng hơn cổ hoặc tay | Sửa ánh sáng trong mặt nạ có chuyển tiếp tự nhiên; giữ bóng dưới hàm. Không làm trắng cả nhóm để ép đồng màu. |
| Mặt mờ nhưng áo rất sắc | Kiểm tra độ phân giải nguồn và số lần resize. Dùng nguồn tốt hơn, resize một lần từ nguồn; không tạo mặt mới để giả nét. |
| Da bệt hoặc mắt sắc giả | Giảm smoothing/sharpening và quay lại bản trước. Chi tiết bổ sung phải đúng vị trí và xuất phát từ nguồn đã căn khớp. |
| Logo to, méo hoặc chữ sai | Đối chiếu đồng phục gốc; giữ tỷ lệ theo thân và phối cảnh. Không tự dựng lại chữ thiếu căn cứ. |

## Điều kiện giao

- Không còn lỗi đã được chỉ ra ở các vùng được giao sửa.
- Tệp đầy đủ kích thước mở được, không xuất nhầm preview; định dạng và profile màu đúng thông báo.
- Bản lớp chỉnh sửa mở được nếu có giao; lớp/mặt nạ còn tác dụng. Không gọi bản phẳng là bản chỉnh sửa có lớp.
- Báo hạn chế nguồn còn tồn tại, phân biệt cải thiện độ tương phản với phục hồi chi tiết thật.
- Khi giữ nguyên vùng đã chốt: kiểm tra sai khác ngoài mặt nạ trên các bản render tương ứng. Nếu không đo được, không tuyên bố sai khác bằng 0.

Ghi kết luận ngắn: đạt/chưa đạt, lỗi cụ thể, vùng cần sửa, giới hạn còn lại. Không dùng một chữ PASS để thay cho bằng chứng đã xem.
