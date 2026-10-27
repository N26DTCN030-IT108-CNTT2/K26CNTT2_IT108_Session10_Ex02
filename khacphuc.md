Xử lý Merge Cell và Hàng trống:

Bỏ Merge Cell: Quét chọn vùng tiêu đề bị gộp, vào thẻ Home > bấm vào mũi tên cạnh nút Merge & Center > chọn Unmerge Cells. Điền lại tiêu đề cho các ô còn thiếu nếu cần.

Xóa hàng trống: Nhấp chuột phải vào dòng trống nằm giữa bảng > chọn Delete > chọn Entire row để loại bỏ hoàn toàn khoảng trống.

Làm sạch khoảng trắng bằng hàm TRIM():

Tạo một cột phụ bên cạnh (ví dụ đặt tên là Trạng thái chuẩn).

Tại ô đầu tiên của cột phụ, nhập công thức: =TRIM(C2) (với C2 là ô chứa trạng thái bị lỗi khoảng trắng) rồi kéo công thức xuống cho toàn bộ bảng.

Cố định dữ liệu: Copy toàn bộ cột phụ vừa làm sạch > bấm chuột phải chọn Paste Options: Values (dán dạng giá trị) đè lên cột "Trạng thái" cũ, sau đó xóa cột phụ đi.

Bật lại AutoFilter:

Bôi đen toàn bộ bảng dữ liệu, vào thẻ Data > chọn Filter (hoặc dùng tổ hợp phím Ctrl + Shift + L) để chắc chắn nút lọc xuất hiện đều trên tất cả các cột.
