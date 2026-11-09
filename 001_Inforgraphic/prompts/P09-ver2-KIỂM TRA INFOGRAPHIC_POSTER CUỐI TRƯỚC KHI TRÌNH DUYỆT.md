# P09 — KIỂM TRA INFOGRAPHIC/POSTER CUỐI TRƯỚC KHI TRÌNH DUYỆT

## 1. Mục đích

Dùng AI làm **biên tập viên phản biện**, giúp phát hiện lỗi văn bản, dữ kiện, hình minh họa, biểu trưng, tính trực quan và rủi ro gây hiểu nhầm của **ảnh đã xuất ra**. AI hỗ trợ rà soát; **không thay người đối chiếu và người có thẩm quyền phê duyệt**.

## 2. Đầu vào cần chuẩn bị

- **ẢNH CUỐI CÙNG:** PNG/JPG hoặc ảnh xuất thực tế muốn rà soát, không chỉ bản mô tả thiết kế.
- **NGUỒN NỘI DUNG:** PDF, văn bản hoặc bảng dữ liệu đã được phép xử lý và có thể đọc được.
- **TÀI NGUYÊN ĐỐI CHIẾU (nếu có):** ảnh địa danh, logo cơ quan, cờ, biểu trưng, tài liệu xác nhận quyền sử dụng hoặc chú thích nguồn ảnh.
- **MỤC ĐÍCH:** [FANPAGE / SLIDE HỘI NGHỊ / IN ẤN / MỤC ĐÍCH KHÁC]; loại ảnh [INFOGRAPHIC / POSTER / TIMELINE / BIỂU ĐỒ / SƠ ĐỒ].

**Lưu ý:** Tệp chưa được cung cấp, không đọc được hoặc không đủ chất lượng thì không được coi là đã xác minh. PDF là nguồn của nội dung nhưng không tự động chứng minh tính chính xác của mọi ảnh minh họa hay tính hợp lệ của quyền sử dụng.

## 3. PROMPT — SAO CHÉP

Bạn là **biên tập viên phản biện hình ảnh tuyên truyền**, chú trọng chính xác nội dung và khả năng đọc trên thiết bị [ĐIỆN THOẠI / MÀN HÌNH TRÌNH CHIẾU / BẢN IN].

Tôi cung cấp:
- **ẢNH CUỐI CÙNG**: [ĐÍNH KÈM TỆP ẢNH].
- **NGUỒN NỘI DUNG**: [PDF / VĂN BẢN / BẢNG DỮ LIỆU].
- **ẢNH/BIỂU TRƯNG ĐỐI CHIẾU** (nếu có): [TỆP ẢNH ĐỊA DANH, LOGO, QUỐC KỲ, CỜ ĐẢNG, ...].
- **MỤC ĐÍCH**: [ĐĂNG FANPAGE / DÙNG TRONG SLIDE / IN ẤN].
- **THỂ LOẠI**: [INFOGRAPHIC / POSTER / TIMELINE / BIỂU ĐỒ / SƠ ĐỒ].

### Nhiệm vụ

**Chỉ đánh giá ảnh thực tế đang đính kèm**, không dựa vào prompt tạo ảnh hay một bản phác thảo trước đó. Đầu tiên, nhận diện tất cả chữ, số, hình ảnh và mối quan hệ có thể đọc rõ trên ảnh; sau đó so với nguồn.

Hãy kiểm tra theo **7 nhóm**, nhưng chỉ áp dụng tiêu chí phù hợp với thể loại ảnh:

**1. Văn bản tiếng Việt**
- Chính tả, dấu thanh, chữ méo/không có nghĩa, tên riêng, tiêu đề, viết hoa và dấu câu.
- Dòng bị cắt, chồng, mờ hoặc quá nhỏ. Khi không đọc chắc một chữ, ghi “không đọc rõ”, không tự suy ra chữ cần có.

**2. Dữ kiện và sự kiện**
- Ngày tháng, tên người, địa danh, thứ tự trước–sau, trạng thái dự kiến/đã xảy ra.
- Phân biệt nội dung nguồn khẳng định với suy luận; không nâng giả thuyết, liên hệ hoặc nhận định có điều kiện thành sự thật.
- Nếu ảnh nêu thông tin không có trong nguồn, ghi **chưa tìm thấy căn cứ trong tài liệu được cung cấp**; không tự kết luận chắc chắn thông tin đó sai.

**3. Số liệu và biểu đồ**
- Đúng từng giá trị, ký hiệu, dấu phân cách, đơn vị, đối tượng, địa bàn, kỳ thống kê.
- Giữ chính xác “ước”, “gần”, “hơn”, “tăng”, “giảm”, “góp phần”; phân biệt tỷ lệ %, số tuyệt đối, số lượt và số người.
- Nếu có biểu đồ: kiểm trục, độ dài cột, nhãn, thang đo, cơ cấu tổng và khả năng so sánh cùng đơn vị. Không tự đặt số liệu không có nguồn.
- Nếu không có biểu đồ, không bắt buộc phải đánh giá lỗi trục/độ dài cột.

**4. Bố cục logic**
- Với timeline: các mốc có đúng thứ tự và không suy ngày từ thời lượng?
- Với quy trình: chiều mũi tên và điều kiện nhánh đúng?
- Với sơ đồ tổ chức: quan hệ cha–con đúng?
- Với ảnh so sánh: tiêu chí và thang đo tương đương?
- Với poster: thông điệp chính nổi bật, không áp máy móc yêu cầu phải có 3–5 khối thông tin.

**5. Hình ảnh và biểu trưng**
- Nếu có ảnh địa danh/công trình: kiểm đặc điểm dễ nhận diện và sự phù hợp với ảnh tham chiếu thực sự được cung cấp.
- Nếu có logo, Quốc kỳ, cờ Đảng, biểu trưng: đối chiếu **tệp chuẩn đính kèm** về hình dạng, màu sắc, chữ và tỷ lệ. **Không có tệp chuẩn thì ghi chưa thể xác minh**, không tự nhận là đã kiểm đúng.
- Nếu là ảnh AI tái hiện sự kiện/hình lịch sử, xác định nguy cơ bị hiểu lầm là ảnh tư liệu hoặc ảnh sự kiện thật; đề xuất nhãn minh họa khi cần.

**6. Khả năng truyền đạt**
- Đúng thể loại và kênh sử dụng; chữ dễ đọc, tương phản tốt, không nhồi chữ, hình ảnh không lấn át thông điệp.
- Kiểm tỷ lệ/kích thước nếu dữ liệu tệp cho phép; không giả định đã đo pixel khi chỉ xem ảnh hiển thị.
- Không áp một khuôn bố cục cố định cho mọi infographic và poster.

**7. Nguồn, quyền sử dụng và trạng thái phát hành**
- Ghi chú nguồn khi cần để người xem hiểu xuất xứ dữ kiện.
- Nguồn ảnh/logo/cờ và quyền sử dụng: chỉ kết luận trong phạm vi giấy phép, thông tin hoặc tệp người dùng cung cấp; không suy từ việc hình xuất hiện trên mạng.
- Không ghi “ĐÃ PHÊ DUYỆT” nếu người dùng chưa cung cấp bằng chứng phê duyệt; bản nháp không thay thế quy trình kiểm duyệt cơ quan.

### Yêu cầu đầu ra

**A. Kết quả ngắn:** Số lỗi nghiêm trọng, số lỗi cần sửa, số gợi ý; nêu nếu nguồn chưa đủ để kiểm.

**B. Bảng vấn đề:**

| Vị trí trên ảnh | Nội dung thực tế quan sát | Lỗi đã xác nhận / điểm chưa thể xác minh | Mức độ | Trang PDF / dòng bảng / tệp gốc | Câu lệnh sửa ảnh |
|---|---|---|---|---|---|

Mức độ: **NGHIÊM TRỌNG** (sai dữ kiện, nhận diện gây hiểu nhầm, lỗi không thể phát hành); **CẦN SỬA** (lỗi ảnh hưởng chất lượng/đọc hiểu); **GỢI Ý** (cải thiện không bắt buộc). Ghi riêng trạng thái **CHƯA THỂ XÁC MINH** trong cột vấn đề; không biến thiếu nguồn thành kết luận sai sự thật.

**C. Kết luận — chọn đúng một:**
1. **CHƯA ĐỦ ĐIỀU KIỆN TRÌNH DUYỆT**: có lỗi trọng yếu hoặc chưa đủ nguồn để đối chiếu nội dung trọng yếu.
2. **CÓ THỂ TRÌNH DUYỆT**: đã đối chiếu được những dữ kiện cốt lõi với nguồn được cung cấp và không phát hiện lỗi trọng yếu. Đây **không phải** quyết định đăng hay phê duyệt của cơ quan.

Nếu không có PDF/bảng dữ kiện hoặc ảnh quá mờ để đọc, **chỉ đánh giá hình thức và ghi rõ giới hạn**, không khẳng định tính đúng của sự kiện/số liệu.

**D. Yêu cầu sửa ảnh:** Với từng lỗi cụ thể, viết lệnh ngắn theo mẫu: “Giữ nguyên toàn bộ các phần khác; tại [vị trí], thay [chữ/hình/giá trị cũ] thành [nội dung có căn cứ].” Không tự điền nội dung sửa nếu nguồn chưa xác nhận.

## 4. Tự kiểm 60 giây dành cho học viên

1. Phóng lớn và đọc **toàn bộ chữ, ngày, đơn vị và số liệu** trên ảnh cuối.
2. Đối chiếu từng dữ kiện quan trọng với **trang PDF/dòng bảng nguồn**, không chỉ ba dữ kiện mẫu.
3. Đối chiếu cờ/logo/ảnh địa danh với **tệp gốc** nếu sử dụng; kiểm nguy cơ ảnh minh họa bị hiểu là ảnh tư liệu.
4. Sửa vùng lỗi, xuất ảnh mới và **chạy lại P09 cho ảnh vừa sửa**.
5. Trình người có trách nhiệm rà soát/phê duyệt theo quy trình; không xem đánh giá AI là quyết định phát hành.

## 5. Những điểm đã cải tiến so với bản P09 cũ

- Giữ **7 nhóm kiểm tra**, nhưng không bắt buộc “3–5 khối” cho poster hoặc áp kiểm biểu đồ cho ảnh không có biểu đồ.
- Phân biệt rõ **lỗi xác nhận từ nguồn** và **điểm chưa thể xác minh**.
- Đối chiếu logo/cờ với **tệp chuẩn thực sự được cung cấp**, không tự tuyên bố đúng/sai khi thiếu tham chiếu.
- Thay “trang PDF” cứng bằng **trang PDF / dòng bảng / tệp gốc** tùy đầu vào.
- Viết lệnh sửa có thể dùng ngay cho P07, nhưng P09 vẫn **độc lập**, không đòi người học mở thêm prompt.
- Duy trì kết luận **đủ/chưa đủ để trình duyệt**, tuyệt đối không nói đã được duyệt hoặc đã sẵn sàng đăng khi chưa có sự đồng ý của cơ quan.
