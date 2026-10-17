# E-commerce UI Improvement

## 1. Giới thiệu

Dự án được thực hiện nhằm khảo sát, phân tích và cải tiến giao diện của website thương mại điện tử Tiki. Sau khi đánh giá các khu vực gồm trang chủ, danh mục sản phẩm, chi tiết sản phẩm, tìm kiếm và giỏ hàng, dự án lựa chọn giao diện giỏ hàng để thực hiện cải tiến bằng HTML5 và CSS3.

Giao diện đề xuất tập trung vào việc giúp người dùng dễ theo dõi tổng chi phí, nhận biết sản phẩm không khả dụng và nắm được số tiền cần mua thêm để đạt điều kiện miễn phí vận chuyển. Đây là giao diện mô phỏng phục vụ mục đích học tập, không phải giao diện chính thức do Tiki phát triển.

## 2. Website tham khảo

- **Tên website:** Tiki
- **URL:** https://tiki.vn/
- **Khu vực đã khảo sát:** Trang chủ, danh mục sản phẩm, chi tiết sản phẩm, chức năng tìm kiếm và giỏ hàng.
- **Khu vực được lựa chọn để cải tiến:** Giỏ hàng trên máy tính và điện thoại.

## 3. Chức năng

- Hiển thị danh sách sản phẩm trong giỏ hàng với hình ảnh, tên sản phẩm, giá bán và số lượng.
- Hiển thị trạng thái hàng hóa, bao gồm sản phẩm còn hàng và sản phẩm không khả dụng.
- Trình bày thông tin tổng kết đơn hàng, gồm tạm tính, giảm giá, phí vận chuyển và tổng thanh toán.
- Hiển thị thanh tiến trình cho biết số tiền cần mua thêm để đạt điều kiện miễn phí vận chuyển.
- Làm nổi bật tổng thanh toán và nút “Xóa tất cả sản phẩm không khả dụng”.
- Điều chỉnh bố cục để phù hợp với màn hình máy tính và điện thoại.

## 4. Công nghệ

- HTML5: Xây dựng cấu trúc và các thành phần của giao diện giỏ hàng.
- CSS3: Thiết kế màu sắc, bố cục, kiểu chữ, các thành phần nổi bật và giao diện tương thích với nhiều kích thước màn hình.
- Chrome DevTools: Mô phỏng màn hình điện thoại để kiểm tra khả năng hiển thị của giao diện.

## 5. Cách chạy

1. Tải hoặc sao chép repository về máy.
2. Giải nén thư mục dự án nếu mã nguồn được tải dưới dạng file ZIP.
3. Mở file index.html bằng trình duyệt web như Google Chrome.
4. Để kiểm tra giao diện trên điện thoại, mở Chrome DevTools bằng cách nhấn F12 hoặc Ctrl + Shift + I trên Windows, sau đó chọn chế độ mô phỏng thiết bị di động. Trên macOS, có thể mở DevTools bằng Command + Option + I.

## 6. Cải tiến đã thực hiện

Dựa trên quá trình khảo sát và trải nghiệm thực tế trên website Tiki, dự án xác định ba vấn đề chính cần cải thiện ở giao diện giỏ hàng: tổng thanh toán chưa đủ nổi bật, người dùng phải xóa từng sản phẩm không khả dụng và giao diện máy tính chưa hiển thị thông tin số tiền cần mua thêm để đạt điều kiện miễn phí vận chuyển như trên điện thoại.

Từ những vấn đề này, giao diện đề xuất được điều chỉnh theo các hướng sau:

- Làm nổi bật tổng thanh toán: Sử dụng nền xanh nhạt, đường viền riêng và cỡ chữ lớn hơn để giúp người dùng dễ nhận biết số tiền dự kiến cần thanh toán.
- Hỗ trợ quản lý sản phẩm không khả dụng: Bổ sung cảnh báo và làm nổi bật nút “Xóa tất cả sản phẩm không khả dụng”, giúp người dùng nhận biết tình trạng hàng hóa và thao tác thuận tiện hơn.
- Bổ sung thông tin miễn phí vận chuyển: Hiển thị thanh tiến trình cùng số tiền cần mua thêm để đạt điều kiện ưu đãi, hỗ trợ người dùng theo dõi chi phí.
- Cải thiện khả năng hiển thị trên thiết bị di động: Sắp xếp giao diện theo bố cục một cột trên màn hình nhỏ, giúp thông tin sản phẩm và tổng kết đơn hàng dễ theo dõi hơn.

## 7. Hỗ trợ từ AI

AI được sử dụng để hỗ trợ phân tích giao diện thương mại điện tử, đề xuất hướng cải tiến và xây dựng mã nguồn HTML/CSS cho giao diện giỏ hàng mô phỏng. Trong quá trình thực hiện, các đề xuất của AI được đối chiếu với website Tiki thông qua trải nghiệm thực tế để xác định những vấn đề có cơ sở và loại bỏ những đề xuất chưa phù hợp với giao diện hiện tại.

Sau khi nhận được mã nguồn ban đầu, giao diện tiếp tục được điều chỉnh để làm nổi bật tổng thanh toán, tăng khả năng nhận biết sản phẩm không khả dụng và hoàn thiện bố cục trên máy tính lẫn điện thoại. Kết quả được kiểm tra bằng trình duyệt và Chrome DevTools nhằm đánh giá khả năng hiển thị ở các kích thước màn hình khác nhau.

AI đóng vai trò là công cụ hỗ trợ phân tích và phát triển giao diện; việc lựa chọn vấn đề, đối chiếu với website thực tế và điều chỉnh kết quả được thực hiện trong quá trình hoàn thiện dự án.

