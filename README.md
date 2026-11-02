
## Buổi 1 – Khảo sát và đề xuất cải tiến giao diện

### 1. Website tham khảo

- **Tên website:** Tiki
- **URL:** https://tiki.vn/
- **Khu vực đã khảo sát:** Trang chủ, danh mục sản phẩm, chi tiết sản phẩm, chức năng tìm kiếm và giỏ hàng.
- **Khu vực được lựa chọn để cải tiến:** Giỏ hàng trên máy tính và điện thoại.

### 2. Chức năng

- Hiển thị danh sách sản phẩm trong giỏ hàng với hình ảnh, tên sản phẩm, giá bán và số lượng.
- Hiển thị trạng thái hàng hóa, bao gồm sản phẩm còn hàng và sản phẩm không khả dụng.
- Trình bày thông tin tổng kết đơn hàng, gồm tạm tính, giảm giá, phí vận chuyển và tổng thanh toán.
- Hiển thị thanh tiến trình cho biết số tiền cần mua thêm để đạt điều kiện miễn phí vận chuyển.
- Làm nổi bật tổng thanh toán và nút “Xóa tất cả sản phẩm không khả dụng”.
- Điều chỉnh bố cục để phù hợp với màn hình máy tính và điện thoại.

### 3. Công nghệ sử dụng

- **HTML5:** Xây dựng cấu trúc và các thành phần của giao diện giỏ hàng.
- **CSS3:** Thiết kế màu sắc, bố cục, kiểu chữ, các thành phần nổi bật và giao diện tương thích với nhiều kích thước màn hình.
- **Chrome DevTools:** Mô phỏng màn hình điện thoại để kiểm tra khả năng hiển thị của giao diện.

### 4. Những cải tiến đã đề xuất

Dựa trên quá trình khảo sát và trải nghiệm thực tế trên website Tiki, dự án xác định ba vấn đề chính cần cải thiện ở giao diện giỏ hàng: tổng thanh toán chưa đủ nổi bật, người dùng phải xóa từng sản phẩm không khả dụng và giao diện máy tính chưa hiển thị thông tin số tiền cần mua thêm để đạt điều kiện miễn phí vận chuyển như trên điện thoại.

Từ những vấn đề này, giao diện đề xuất được điều chỉnh theo các hướng sau:

- **Làm nổi bật tổng thanh toán:** Sử dụng nền xanh nhạt, đường viền riêng và cỡ chữ lớn hơn để giúp người dùng dễ nhận biết số tiền dự kiến cần thanh toán.
- **Hỗ trợ quản lý sản phẩm không khả dụng:** Bổ sung cảnh báo và làm nổi bật nút “Xóa tất cả sản phẩm không khả dụng”.
- **Bổ sung thông tin miễn phí vận chuyển:** Hiển thị thanh tiến trình cùng số tiền cần mua thêm để đạt điều kiện ưu đãi.
- **Cải thiện giao diện trên thiết bị di động:** Sắp xếp giao diện theo bố cục một cột trên màn hình nhỏ.

### 5. Hỗ trợ từ AI

AI được sử dụng để hỗ trợ phân tích giao diện thương mại điện tử, đề xuất hướng cải tiến và xây dựng mã nguồn HTML/CSS cho giao diện giỏ hàng mô phỏng. Trong quá trình thực hiện, các đề xuất của AI được đối chiếu với website Tiki thông qua trải nghiệm thực tế để xác định những vấn đề có cơ sở và loại bỏ những đề xuất chưa phù hợp với giao diện hiện tại.

AI đóng vai trò là công cụ hỗ trợ phân tích và phát triển giao diện; việc lựa chọn vấn đề, đối chiếu với website thực tế và điều chỉnh kết quả được thực hiện trong quá trình hoàn thiện dự án.

---

## Buổi 2 – Thực hành và hoàn thiện giao diện bằng HTML5/CSS3

### 1. Nội dung thực hành

Tiếp tục phát triển giao diện giỏ hàng đã đề xuất ở Buổi 1, tập trung vào việc tổ chức mã nguồn CSS, định dạng các thành phần và điều chỉnh bố cục để giao diện hiển thị phù hợp trên nhiều kích thước màn hình.

### 2. Các kỹ thuật HTML5/CSS3 đã thực hành

- **Liên kết tệp CSS:** Tạo tệp `style.css` riêng và liên kết với `index.html` để quản lý phần định dạng giao diện.
- **CSS Selectors:** Sử dụng các bộ chọn để xác định và định dạng từng thành phần trên trang web.
- **Box Model:** Sử dụng `margin`, `padding`, `border` và các thuộc tính kích thước để điều chỉnh khoảng cách, đường viền và không gian của các thành phần.
- **Flexbox:** Sắp xếp và căn chỉnh các thành phần theo hàng hoặc cột, chẳng hạn như khu vực giá bán và số lượng sản phẩm.
- **CSS Grid:** Chia bố cục danh sách sản phẩm thành hai cột và sắp xếp khu vực sản phẩm bên cạnh bảng tổng kết đơn hàng.
- **Responsive Design:** Sử dụng `@media` để điều chỉnh bố cục theo kích thước màn hình, giúp giao diện phù hợp với máy tính và điện thoại.
- **Hover và Focus:** Bổ sung hiệu ứng khi di chuột và khi người dùng điều hướng bằng bàn phím.

### 3. Những thay đổi đã thực hiện

Trong Buổi 2, mã nguồn CSS được tiếp tục điều chỉnh để hoàn thiện cách hiển thị của giao diện giỏ hàng. Một số thay đổi đáng chú ý gồm:

- **Điều chỉnh bố cục sản phẩm:** Sử dụng CSS Grid để sắp xếp các thẻ sản phẩm thành hai cột trên màn hình lớn và chuyển thành một cột khi màn hình có chiều rộng nhỏ hơn hoặc bằng 520px.
- **Điều chỉnh thẻ sản phẩm:** Sử dụng Box Model để kiểm soát khoảng cách, đường viền, kích thước và hiệu ứng đổ bóng của từng thẻ.
- **Sắp xếp thông tin sản phẩm:** Sử dụng Flexbox để bố trí giá bán và số lượng sản phẩm, đồng thời điều chỉnh hướng sắp xếp trên màn hình nhỏ.
- **Cải thiện khả năng tương thích:** Sử dụng các quy tắc `@media` để điều chỉnh bố cục giỏ hàng và kích thước thành phần theo từng kích thước màn hình.
- **Bổ sung hiệu ứng tương tác:** Sử dụng `:hover` và `:focus-visible` để tạo hiệu ứng trực quan khi di chuột hoặc điều hướng bằng bàn phím.

### 4. Hướng dẫn chạy website

1. Tải hoặc sao chép repository về máy tính.
2. Giải nén thư mục dự án nếu mã nguồn được tải dưới dạng file ZIP.
3. Đảm bảo các tệp `index.html` và `style.css` nằm cùng thư mục.
4. Mở file `index.html` bằng trình duyệt web như Google Chrome.
5. Để kiểm tra giao diện trên điện thoại, mở Chrome DevTools bằng cách nhấn `F12` hoặc `Ctrl + Shift + I` trên Windows. Trên macOS, sử dụng `Command + Option + I`, sau đó chọn chế độ mô phỏng thiết bị di động.

### 5. Công cụ AI và cách kiểm tra kết quả

ChatGPT được sử dụng để hỗ trợ giải thích các thuộc tính HTML/CSS, hướng dẫn cách tổ chức mã nguồn và đề xuất điều chỉnh bố cục giao diện. Các nội dung được xem xét trước khi áp dụng vào dự án.

Sau khi chỉnh sửa, giao diện được kiểm tra bằng trình duyệt và Chrome DevTools nhằm quan sát khả năng hiển thị trên các kích thước màn hình khác nhau. Các kết quả được đối chiếu với yêu cầu bài tập và điều chỉnh lại khi cần thiết.

### 6. Đường dẫn dự án

- **GitHub Repository:** (https://github.com/vynguyen31241024413-creator/ecommerce-ui-improvement)
- **Website triển khai:** (https://vynguyen31241024413-creator.github.io/ecommerce-ui-improvement/)

---

