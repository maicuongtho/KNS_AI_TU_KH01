# P03 — THIẾT KẾ NGƯỢC TỪ ẢNH THAM KHẢO (BẢN ĐẦY ĐỦ)

## Dùng khi nào?

Bạn có một ảnh infographic/poster đẹp nhưng chưa biết mô tả bố cục và phong cách cho AI. Thay vì viết prompt từ đầu, hãy **đưa ảnh mẫu cho AI phân tích**, rồi yêu cầu tạo một ảnh mới với **nội dung của mình**.

**Đầu vào tối thiểu**

1. **Ảnh A — Ảnh tham khảo:** ảnh dùng để học cách bố trí, màu sắc và cách trình bày; chỉ sử dụng khi có quyền tham khảo phù hợp.  
2. **Nguồn B — Nội dung mới:** PDF, văn bản hoặc bảng số liệu được phép xử lý, có thông tin muốn đưa lên ảnh.  
3. **Mục tiêu:** \[CHỦ ĐỀ\], \[NGƯỜI XEM\], \[KÊNH SỬ DỤNG\].

**Đầu vào tùy chọn:** Ảnh C1, C2… là **ảnh thực tế, logo, cờ hoặc biểu trưng muốn xuất hiện trong ảnh mới**. Đây là tài nguyên cần dùng cho sản phẩm, **khác với ảnh A chỉ để tham khảo phong cách**.

**Đầu ra:** Phân tích rất ngắn ảnh mẫu → prompt thiết kế mới có thể tái sử dụng → **01 ảnh mới được tạo trực tiếp**. Tỷ lệ mặc định **4:5**, có thể thay khi cần.

---

## PROMPT — SAO CHÉP VÀ ĐIỀN CHỖ \[ \]

Bạn là **Creative Director kiêm nhà thiết kế infographic**. Tôi cung cấp:

- **Ảnh A:** ảnh tham khảo để học ngôn ngữ thị giác, không dùng làm nguồn nội dung.  
- **Nguồn B:** \[PDF / VĂN BẢN / BẢNG SỐ LIỆU\] về **\[CHỦ ĐỀ MỚI\]**, được phép xử lý.  
- **Đối tượng:** \[NGƯỜI XEM\]. **Mục tiêu:** \[ĐIỀU NGƯỜI XEM CẦN HIỂU / NHỚ / LÀM\].  
- **Kênh sử dụng:** \[FANPAGE / SLIDE / IN ẤN\]. **Tỷ lệ ảnh:** \[4:5 / 16:9 / 2:3\].  
- **Ảnh C (nếu có):** \[ẢNH ĐỊA DANH / ẢNH SỰ KIỆN / LOGO / CỜ / BIỂU TRƯNG ĐÍNH KÈM\] cần sử dụng trong thiết kế mới; nêu rõ ảnh nào là tài nguyên phải giữ đúng.

**Hãy thực hiện liên tục ba bước trong cùng một yêu cầu:**

### 1\. Phân tích ảnh tham khảo A

Trình bày ngắn gọn (tối đa 6 ý):

- Loại thiết kế, bố cục và hướng đọc;  
- Thứ bậc tiêu đề, số liệu, hình minh họa và các khối nội dung;  
- Bảng màu, phong cách hình ảnh, khoảng trắng;  
- Điểm khiến ảnh dễ hoặc khó đọc trên điện thoại;  
- **3 đặc điểm thiết kế nên học hỏi**.

Không lấy dữ kiện, tên riêng, số liệu, logo, khẩu hiệu hoặc ảnh tư liệu từ A làm nội dung cho ảnh mới.

### 2\. Đảo ngược thành prompt thiết kế mới

Viết **01 prompt tạo ảnh ngắn, dùng lại được**, mô tả bố cục, tỷ lệ, phong cách và **chính xác những nội dung chữ dự kiến đưa lên ảnh** dựa trên **nguồn B**.

- Chọn **3–5 ý chính** khi nguồn phù hợp; nếu là poster chỉ cần một thông điệp, nếu là timeline/quy trình thì giữ đủ các mốc/bước thiết yếu và tránh nhồi chữ.  
- **Học nguyên tắc thiết kế** từ A, nhưng điều chỉnh cho phù hợp nội dung B; không sao chép nguyên bản các chi tiết nhận diện riêng.  
- Nếu có ảnh C, sử dụng đúng các ảnh đính kèm theo yêu cầu; với logo/cờ/biểu trưng, phải kiểm tra hình dạng và màu sắc, không tự thay bằng mẫu khác.  
- Không bịa ngày, số liệu, địa danh, quan hệ hoặc sự kiện; giữ nguyên các từ hạn định như “ước”, “hơn”, “gần”, cùng thời điểm và đơn vị.  
- Nếu không đọc được ảnh A hoặc nội dung B, nêu rõ phần thiếu, không giả vờ đã phân tích hay sử dụng nguồn.

### 3\. Trực tiếp tạo ảnh mới

**Hãy tạo ngay 01 ảnh hoàn chỉnh** theo prompt ở bước 2; không dừng ở khâu tư vấn hoặc trả về mã nguồn. Tỷ lệ **\[4:5 hoặc tỷ lệ đã chọn\]**, chữ tiếng Việt rõ ràng, đúng dấu, đủ tương phản và đọc được trên điện thoại.

Ảnh mới phải có **nội dung từ B**, đồng thời kế thừa được **tinh thần bố cục và phong cách của A**. Nếu ảnh lịch sử được minh họa bằng AI, không trình bày như ảnh tư liệu thật. Với tài nguyên C, giữ đúng ảnh gốc trong khả năng công cụ; nếu không bảo đảm, nêu rõ giới hạn thay vì khẳng định đã giữ nguyên.

**Sau khi tạo ảnh:**

- Nêu ngắn **3 đặc điểm đã học từ ảnh A**.  
- Liệt kê **các dữ kiện trên ảnh mới và trang PDF/vị trí trong B** để tôi kiểm tra; không tự đặt số trang nếu nguồn không có.  
- Nêu **3 điểm cần soát trước khi đăng** (chữ, số liệu, hình ảnh/biểu trưng).

Nếu công cụ hiện tại không hỗ trợ tạo ảnh, hãy nói rõ và chỉ cung cấp prompt đã đảo ngược; không nhận là đã xuất ảnh.

---

## Tự kiểm sau khi chạy

- [ ] AI phân tích đúng **bố cục, phong cách** của ảnh mẫu A?  
- [ ] Ảnh mới dùng **nội dung từ B**, không mang nhầm dữ kiện và nhận diện từ A?  
- [ ] Có trực tiếp tạo **ảnh thật** chứ không chỉ trả lời bằng văn bản?  
- [ ] Chữ tiếng Việt và các số liệu, mốc thời gian đã đối chiếu nguồn B?  
- [ ] Nếu dùng ảnh C, ảnh địa danh và biểu trưng có đúng theo tệp cung cấp?

**Gợi ý:** Học viên chọn một ảnh mẫu có bố cục dễ đọc, đưa một nội dung mới vào cùng cuộc trò chuyện, sau đó đối chiếu ảnh kết quả với ảnh mẫu về **cách trình bày**, không phải về dữ kiện. Đây là cách “đảo ngược quy trình” khi chưa biết viết prompt thiết kế.