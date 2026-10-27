Vi phạm quy tắc "Không gộp ô tiêu đề" (Merge Cell):

Thực trạng: Bảng dữ liệu có các ô bị gộp (Merge Cell) ở hàng tiêu đề.

Hậu quả: Khi bật AutoFilter, Excel chỉ nhận diện và áp dụng bộ lọc cho khối ô đầu tiên bị gộp, khiến các cột còn lại mất nút lọc hoặc bị ngắt quãng, không lọc được toàn bộ bảng.

Vi phạm quy tắc "Không để hàng/cột trống (Blank rows/columns)" giữa vùng dữ liệu:

Thực trạng: Có hàng trống nằm ngay giữa bảng dữ liệu.

Hậu quả: Khi bấm tổ hợp phím Ctrl + Shift + L để lọc, Excel hiểu nhầm rằng vùng dữ liệu bị ngắt đoạn tại hàng trống đó và chỉ chọn phạm vi từ trên xuống đến dòng trống, làm biến mất nút Filter ở các dòng phía dưới.

Vi phạm quy tắc "Đồng nhất định dạng và tính toàn vẹn dữ liệu" (Dữ liệu rác/Khoảng trắng vô hình):

Thực trạng: Cột "Trạng thái" có chứa các khoảng trắng thừa ("hỏng " và "hỏng").

Hậu quả: Dù nhìn bằng mắt thường thấy giống nhau nhưng Excel coi đây là hai giá trị hoàn toàn khác nhau, khiến bộ lọc tách thành 2 nhóm riêng biệt.
