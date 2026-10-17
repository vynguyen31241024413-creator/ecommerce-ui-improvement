# AI Usage Log

## 1. Công cụ AI

- **Tên công cụ:** ChatGPT (OpenAI)

## 2. Mục đích sử dụng

ChatGPT được sử dụng trong hai giai đoạn chính của dự án.

Thứ nhất, AI hỗ trợ phân tích các khu vực trên website Tiki, bao gồm trang chủ, danh mục sản phẩm, chi tiết sản phẩm, tìm kiếm và giỏ hàng. Kết quả phân tích giúp xác định những điểm thuận tiện, các vấn đề có thể phát sinh và những hướng cải tiến cần xem xét.

Thứ hai, AI hỗ trợ xây dựng giao diện giỏ hàng bằng HTML5 và CSS3. Trong quá trình hoàn thiện, AI được sử dụng để điều chỉnh bố cục trên máy tính và điện thoại, làm nổi bật tổng thanh toán, bổ sung cảnh báo sản phẩm không khả dụng và thể hiện thông tin về điều kiện miễn phí vận chuyển.

## 3. Prompt đã sử dụng

Các prompt chính được sử dụng trong quá trình thực hiện dự án gồm:

**Prompt 1: Phân tích giao diện website**

“Hãy giúp tôi lập bảng phân tích các khu vực: trang chủ, danh mục sản phẩm, chi tiết sản phẩm, tìm kiếm và giỏ hàng. Với mỗi khu vực, hãy nêu mục đích của chức năng, thành phần giao diện cần có, điểm thuận tiện đối với khách hàng, một vấn đề có thể phát sinh và một đề xuất cải tiến. Không khẳng định những tính năng chưa được kiểm chứng. Phân biệt rõ nhận xét dựa trên quan sát và đề xuất của AI.”

**Prompt 2: Nhờ đề xuất giao diện**
"Tôi đang thực hiện bài tập phát triển giao diện website thương mại điện tử
bằng HTML5 và CSS3.

Tôi muốn cải tiến khu vực: giỏ hàng.

Đối tượng sử dụng: khách hàng mua sắm trực tuyến tại Việt Nam.

Hãy đề xuất:
1. Bố cục giao diện.
2. Các thành phần HTML cần sử dụng.
3. Cách tổ chức CSS.
4. Cách hiển thị trên máy tính và điện thoại.
5. Những điểm cần kiểm tra về khả năng sử dụng.

Trước tiên, hãy giải thích phương án thiết kế.
Chưa tạo toàn bộ mã nguồn cho đến khi tôi yêu cầu."

**Prompt 3: Nhờ AI hỗ trợ tạo mã HTML/CSS.**
"Dựa trên phương án đã thống nhất, hãy tạo một trang giao diện
thương mại điện tử bằng HTML5 và CSS3.

Yêu cầu:
- Giao diện có tiêu đề và khu vực sản phẩm.
- Có tối thiểu 4 sản phẩm mẫu.
- Mỗi sản phẩm có hình ảnh, tên, giá và nút thao tác.
- Bố cục phù hợp với màn hình máy tính và điện thoại.
- Mã HTML có cấu trúc rõ ràng.
- CSS được tách thành file riêng.
- Không sử dụng backend hoặc cơ sở dữ liệu.
- Không đưa thư viện hoặc thành phần không cần thiết vào dự án.

Giải thích cách chạy trang web và những phần tôi cần kiểm tra."

**Prompt 4: Cải tiến thao tác với sản phẩm không khả dụng**
"Hãy điều chỉnh giao diện để bổ sung cảnh báo đối với sản phẩm không khả dụng và làm nổi bật nút “Xóa tất cả sản phẩm không khả dụng”, giúp người dùng dễ nhận biết và thuận tiện hơn khi quản lý giỏ hàng."

**Prompt 5: Làm nổi bật tổng thanh toán**

"Hãy điều chỉnh phần tổng kết đơn hàng, làm nổi bật số tiền cần thanh toán bằng cách thay đổi nền, đường viền và kích thước chữ, đồng thời giữ bố cục rõ ràng trên các kích thước màn hình khác nhau."

## 4. Kết quả AI đề xuất

AI đề xuất giao diện giỏ hàng gồm danh sách sản phẩm và khu vực tóm tắt đơn hàng; thể hiện tạm tính, giảm giá, phí vận chuyển và tổng thanh toán; làm rõ trạng thái sản phẩm không khả dụng; bổ sung thanh tiến trình vận chuyển; và sử dụng CSS media queries để sắp xếp lại bố cục trên màn hình nhỏ.

## 5. Kiểm tra và điều chỉnh

Các đề xuất của AI không được sử dụng hoàn toàn mà được đối chiếu với kết quả khảo sát thực tế trên website Tiki.

- **Trang chủ:** AI nhận xét giao diện có mật độ thông tin khá cao do nhiều banner, widget nổi như “Trợ lý”, “Tin mới” và các nhãn khuyến mãi trên thẻ sản phẩm. Tuy nhiên, qua trải nghiệm thực tế, các widget nổi chưa gây ảnh hưởng đáng kể đến việc xem sản phẩm, đồng thời chưa có cơ sở kết luận website tải chậm khi chưa đo lường tốc độ. Vì vậy, có thể cân nhắc sắp xếp các khu vực khuyến mãi hợp lý hơn thay vì thay đổi cách hiển thị widget.

- **Danh mục sản phẩm:** Tiki cung cấp nhiều tiêu chí lọc như họa tiết, màu sắc, kích cỡ, dịch vụ và đánh giá, hỗ trợ người dùng thu hẹp kết quả tìm kiếm. Tuy nhiên, khi kết hợp nhiều tiêu chí, website có thể trả về kết quả rỗng. AI đề xuất bổ sung nút “Xóa tất cả bộ lọc”, nhưng qua kiểm tra, Tiki đã có sẵn chức năng này. Do đó, hướng cải tiến phù hợp hơn là gợi ý người dùng điều chỉnh hoặc nới lỏng tiêu chí lọc khi không tìm thấy sản phẩm.

- **Chi tiết sản phẩm:** Giao diện hiển thị hình ảnh, giá bán, đánh giá, các lựa chọn phân loại và nút mua hàng. AI đề xuất bổ sung thanh mua hàng cố định khi cuộn trang, nhưng qua đối chiếu, Tiki đã tích hợp chức năng này. Bên cạnh đó, chưa ghi nhận vấn đề đáng kể khi thay đổi màu sắc hoặc kích thước sản phẩm. Vì vậy, các đề xuất trên chưa đủ cơ sở để xem là những cải tiến cần thiết.

- **Tìm kiếm:** Tiki có tốc độ gợi ý từ khóa nhanh và khả năng tự động sửa một số lỗi chính tả đơn giản. Tuy nhiên, qua thử nghiệm với từ khóa “sách học tiếng Việt cho người nước ngoài”, một số kết quả như sách HSK, sách học tiếng Anh cho người định cư nước ngoài và sách từ vựng IELTS 8.0 chưa thực sự phù hợp với nhu cầu ban đầu. Điều này cho thấy mức độ liên quan của kết quả tìm kiếm vẫn có thể được cải thiện để đáp ứng chính xác hơn mong muốn của người dùng.

- **Giỏ hàng:** Giao diện hiển thị sản phẩm, số lượng, giá bán và tổng chi phí cần thanh toán. Tuy nhiên, tổng thanh toán chưa đủ nổi bật và người dùng phải xóa từng sản phẩm không khả dụng. Ngoài ra, trong lần thử nghiệm, thanh thông báo số tiền cần mua thêm để đạt điều kiện miễn phí vận chuyển được ghi nhận trên điện thoại nhưng chưa thấy trên máy tính. Vì vậy, giao diện cải tiến tập trung làm nổi bật tổng thanh toán, bổ sung cảnh báo cùng nút “Xóa tất cả sản phẩm không khả dụng” và hiển thị thanh tiến trình miễn phí vận chuyển. Nhận xét về mã giảm giá chưa tối ưu không được giữ lại vì mã áp dụng sẵn đã là lựa chọn tốt nhất trong trường hợp kiểm tra.

## 6. Phần tôi hiểu và có thể giải thích

- **HTML5 (index.html):** Xây dựng cấu trúc giao diện, bao gồm khu vực danh sách sản phẩm, thông tin từng sản phẩm, cảnh báo hàng hóa và bảng tổng kết đơn hàng.

- **CSS3 (ss/style.css):** Quy định màu sắc, kích thước, khoảng cách, đường viền và cách sắp xếp các thành phần giao diện.

- **Cách tổ chức các thành phần bằng div và class:** Thẻ div giúp nhóm nhiều thành phần có liên quan vào cùng một khu vực, ví dụ nhóm thông tin của một sản phẩm hoặc nhóm các khoản phí trong bảng tổng kết. Thuộc tính class dùng để đặt tên cho các nhóm này, giúp CSS xác định đúng khu vực cần chỉnh sửa mà không ảnh hưởng đến toàn bộ trang web.

- **Cách sắp xếp bố cục bằng Flexbox:** Flexbox giúp sắp xếp các thành phần theo hàng hoặc cột và căn chỉnh khoảng cách giữa chúng. Trong giao diện giỏ hàng, kỹ thuật này hỗ trợ bố trí danh sách sản phẩm bên cạnh bảng tổng kết trên máy tính, đồng thời giúp các thành phần bên trong mỗi sản phẩm được sắp xếp gọn gàng.

- **Cách làm nổi bật tổng thanh toán bằng CSS:** Tổng thanh toán được thiết kế nổi bật hơn bằng cách thay đổi màu nền, đường viền và kích thước chữ. Việc kết hợp các thuộc tính như background, border, font-size và font-weight giúp người dùng dễ nhận ra số tiền cuối cùng cần thanh toán mà không phải tìm kiếm giữa nhiều thông tin khác.

- **Cách điều chỉnh giao diện bằng @media:** Quy tắc @media cho phép áp dụng những kiểu CSS khác nhau tùy theo kích thước màn hình. Chẳng hạn, trên máy tính, danh sách sản phẩm và bảng tổng kết có thể nằm cạnh nhau; khi chuyển sang màn hình điện thoại, bố cục được điều chỉnh thành một cột để nội dung không bị chật hoặc tràn khỏi màn hình.
