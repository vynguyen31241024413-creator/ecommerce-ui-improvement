# AI Usage Log
## BUỔI 1

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


## BUỔI 2

**Prompt 6: Kiểm tra việc liên kết tệp CSS với HTML**

Tôi đang có hai tệp index.html và style.css trong cùng một thư mục dự án. Hãy hướng dẫn tôi cách liên kết tệp CSS với HTML bằng thẻ link trong phần head. Giải thích ý nghĩa của từng thuộc tính trong đoạn mã liên kết và hướng dẫn cách kiểm tra trên Google Chrome DevTools để biết trình duyệt đã tải tệp CSS thành công hay chưa. Hãy chỉ rõ cách nhận biết trường hợp đường dẫn bị sai.

**Prompt 7: Giải thích CSS Selectors và Box Model**

Hãy giải thích cách sử dụng CSS Selectors và Box Model trong giao diện giỏ hàng của tôi. Làm rõ cách các bộ chọn như .product-card, .product-card h3 và .price-block strong xác định những thành phần cần định dạng.

Đồng thời, giải thích vai trò của các thuộc tính margin, padding, border, width và height. Hãy lấy ví dụ trực tiếp từ thẻ sản phẩm trong giao diện để tôi hiểu cách điều chỉnh khoảng cách, kích thước và đường viền mà không làm ảnh hưởng đến những khu vực khác.

**Prompt 8: Giải thích cách sử dụng Flexbox**

Trong giao diện giỏ hàng, tôi sử dụng Flexbox để sắp xếp khu vực giá bán và số lượng sản phẩm. Hãy giải thích cách hoạt động của display: flex, justify-content, align-items và gap.

Ví dụ, với đoạn CSS:

.product-bottom {
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 16px;
}

Hãy giải thích vai trò của từng thuộc tính, cách chúng phối hợp với nhau và kết quả hiển thị trong giao diện. Trình bày theo cách dễ hiểu để sinh viên có thể tự giải thích lại khi giảng viên hỏi.

**Prompt 9: Giải thích cách sử dụng CSS Grid**

Tôi đang sử dụng CSS Grid để bố trí danh sách sản phẩm và khu vực tổng kết đơn hàng. Hãy giải thích cách hoạt động của display: grid, grid-template-columns và gap trong đoạn mã CSS của tôi.

Đặc biệt, hãy giải thích ý nghĩa của:

.product-section {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 16px;
}

Trình bày cách hai cột sản phẩm được hình thành, ý nghĩa của repeat(), minmax(), 1fr và khoảng cách giữa các thẻ. Sau đó giải thích cách thay đổi bố cục thành một cột trên màn hình nhỏ bằng CSS Media Query. Viết thành các đoạn văn phù hợp để đưa vào báo cáo thực hành.

**Prompt 10: Giải thích Responsive Design và Media Query**

Tôi muốn giao diện giỏ hàng hiển thị phù hợp trên cả máy tính và điện thoại. Hãy giải thích cách sử dụng @media trong CSS để thay đổi bố cục theo chiều rộng màn hình.

Dựa trên mã CSS hiện tại của tôi, hãy phân tích cách điều chỉnh .cart-layout, .product-section, .product-card, .product-image và .product-bottom khi kích thước màn hình giảm xuống.

Hãy giải thích sự khác nhau giữa việc chuyển bố cục tổng thể thành một cột và việc chuyển danh sách sản phẩm từ hai cột thành một cột. Không tự thay đổi các giá trị breakpoint nếu không có lý do cụ thể.

**Prompt 11: Giải thích hiệu ứng Hover và Focus**

Hãy giải thích cách sử dụng :hover và :focus-visible trong CSS để cải thiện khả năng tương tác của giao diện giỏ hàng.

Tôi muốn hiểu cách áp dụng hiệu ứng khi người dùng di chuột vào thẻ sản phẩm hoặc nút thanh toán, cũng như khi người dùng sử dụng bàn phím để điều hướng đến nút thao tác. Hãy giải thích sự khác nhau giữa hai trạng thái này, ý nghĩa của các thuộc tính CSS thường dùng và cách kiểm tra trực tiếp trên trình duyệt.

**Prompt 12: Hỗ trợ điều chỉnh mã CSS hiện tại**

Tôi sẽ cung cấp mã CSS mới nhất của giao diện giỏ hàng. Hãy đọc và phân tích đúng theo mã nguồn tôi gửi, không sử dụng lại các phiên bản CSS cũ.

Hãy kiểm tra cách tổ chức bố cục, kích thước thẻ sản phẩm, hình ảnh, vị trí nút xóa, khoảng cách giữa các thành phần và các quy tắc Responsive Design. Khi giải thích hoặc đề xuất thay đổi, hãy chỉ rõ selector và thuộc tính liên quan. Không tự thêm những thuộc tính mà mã nguồn hiện tại chưa có hoặc khẳng định một thay đổi đã được thực hiện khi chưa có căn cứ.

**4. Phần tự kiểm tra và điều chỉnh của cá nhân**

Sau khi tham khảo kết quả từ ChatGPT, em chủ động kiểm tra và điều chỉnh mã nguồn để phù hợp với yêu cầu bài tập và giao diện mong muốn.

Đối với mã nguồn HTML/CSS: Em kiểm tra cấu trúc tệp dự án, bảo đảm index.html và style.css được đặt đúng vị trí và liên kết với nhau.

Đối với bố cục sản phẩm: Em điều chỉnh CSS Grid để danh sách sản phẩm hiển thị thành hai cột trên màn hình lớn và chuyển thành một cột khi chiều rộng màn hình nhỏ hơn hoặc bằng 520px.

Đối với thẻ sản phẩm: Em điều chỉnh kích thước, khoảng cách, hình ảnh, đường viền và hiệu ứng đổ bóng để các sản phẩm được trình bày rõ ràng hơn.

Đối với thông tin sản phẩm: Em điều chỉnh Flexbox để sắp xếp giá bán và số lượng; trên màn hình nhỏ, các thành phần được chuyển sang bố cục theo chiều dọc.

Đối với nút thao tác: Em điều chỉnh vị trí nút xóa bằng cách kết hợp position: relative ở thẻ sản phẩm và position: absolute ở nút, giúp nút nằm ở góc trên bên phải của từng thẻ.

Đối với giao diện điện thoại: Tôi điều chỉnh các quy tắc @media để thay đổi bố cục tổng thể, kích thước hình ảnh, chữ và khoảng cách giữa các thành phần.

Đối với việc kiểm tra kết quả: Em sử dụng trình duyệt và Chrome DevTools để quan sát giao diện ở các kích thước màn hình khác nhau, từ đó tiếp tục chỉnh sửa những vị trí chưa hiển thị như mong muốn.

