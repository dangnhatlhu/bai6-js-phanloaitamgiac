# Phân loại tam giác đều

## Các câu prompt khi chạy chương trình

Chương trình lần lượt hiển thị ba hộp thoại để nhập:

1. `Nhập độ dài cạnh thứ nhất:`
2. `Nhập độ dài cạnh thứ hai:`
3. `Nhập độ dài cạnh thứ ba:`

Sau khi nhập xong, chương trình thông báo nếu thao tác bị hủy, dữ liệu không hợp lệ, ba cạnh không tạo thành tam giác, tam giác đều hoặc không phải tam giác đều.

## Giải thích từng dòng trong `index.html`

| Dòng | Giải thích |
|---:|---|
| 1 | Khai báo tài liệu theo chuẩn HTML5. |
| 2 | Bắt đầu phần tử HTML và đặt ngôn ngữ trang là tiếng Việt. |
| 3 | Mở phần khai báo thông tin của trang. |
| 4 | Khai báo bảng mã UTF-8 để hiển thị tiếng Việt đúng. |
| 5 | Thiết lập khung nhìn phù hợp với chiều rộng thiết bị, hỗ trợ hiển thị trên di động. |
| 6 | Đặt tiêu đề trang trên tab trình duyệt. |
| 7 | Đóng phần khai báo thông tin trang. |
| 8 | Bắt đầu phần nội dung hiển thị của trang. |
| 9 | Hiển thị tiêu đề chính. |
| 10 | Hướng dẫn người dùng nhập ba cạnh qua các hộp thoại. |
| 11 | Dòng trống để phân tách phần nội dung HTML và mã JavaScript. |
| 12 | Mở thẻ chứa JavaScript chạy trực tiếp trong trang. |
| 13 | Hiện hộp thoại prompt để nhập cạnh thứ nhất và lưu dữ liệu dạng chuỗi. |
| 14 | Hiện hộp thoại prompt để nhập cạnh thứ hai và lưu dữ liệu dạng chuỗi. |
| 15 | Hiện hộp thoại prompt để nhập cạnh thứ ba và lưu dữ liệu dạng chuỗi. |
| 16 | Dòng trống để phân tách phần nhập dữ liệu và phần kiểm tra. |
| 17 | Kiểm tra xem người dùng có bấm Hủy ở bất kỳ hộp thoại nhập nào không. |
| 18 | Nếu có thao tác hủy, hiển thị thông báo và không tiếp tục phân loại. |
| 19 | Nếu không hủy, bắt đầu khối xử lý dữ liệu đã nhập. |
| 20 | Chuyển chuỗi cạnh thứ nhất sang kiểu số. |
| 21 | Chuyển chuỗi cạnh thứ hai sang kiểu số. |
| 22 | Chuyển chuỗi cạnh thứ ba sang kiểu số. |
| 23 | Dòng trống để phân tách chuyển đổi dữ liệu và kiểm tra hợp lệ. |
| 24 | Bắt đầu điều kiện kiểm tra dữ liệu nhập. |
| 25 | Kiểm tra cả ba giá trị có phải là số hữu hạn hay không; giá trị không phải số và vô cực đều bị loại. |
| 26 | Kiểm tra cạnh thứ nhất phải lớn hơn 0. |
| 27 | Kiểm tra cạnh thứ hai phải lớn hơn 0. |
| 28 | Kiểm tra cạnh thứ ba phải lớn hơn 0. |
| 29 | Kết thúc biểu thức điều kiện dữ liệu không hợp lệ. |
| 30 | Nếu dữ liệu không hợp lệ, hiển thị yêu cầu nhập ba số dương. |
| 31 | Nếu dữ liệu hợp lệ, chuyển sang kiểm tra điều kiện tạo thành tam giác. |
| 32 | Kiểm tra tổng cạnh thứ nhất và thứ hai phải lớn hơn cạnh thứ ba. |
| 33 | Kiểm tra tổng cạnh thứ nhất và thứ ba phải lớn hơn cạnh thứ hai. |
| 34 | Kiểm tra tổng cạnh thứ hai và thứ ba phải lớn hơn cạnh thứ nhất. |
| 35 | Kết thúc biểu thức kiểm tra điều kiện tam giác. |
| 36 | Nếu không thỏa bất đẳng thức tam giác, thông báo ba cạnh không tạo thành tam giác. |
| 37 | Nếu là tam giác, kiểm tra cạnh thứ nhất bằng cạnh thứ hai và cạnh thứ hai bằng cạnh thứ ba. |
| 38 | Nếu cả ba cạnh bằng nhau, thông báo đây là tam giác đều. |
| 39 | Nếu ba cạnh không đồng thời bằng nhau, chuyển sang nhánh còn lại. |
| 40 | Thông báo ba cạnh không bằng nhau nên đây không phải tam giác đều. |
| 41 | Đóng nhánh kiểm tra tam giác đều. |
| 42 | Đóng khối xử lý khi người dùng không hủy. |
| 43 | Đóng thẻ JavaScript. |
| 44 | Đóng phần nội dung trang. |
| 45 | Đóng tài liệu HTML. |
