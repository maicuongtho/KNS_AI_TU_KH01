# P08 — TẠO CÁC TỶ LỆ ẢNH TỪ BẢN GỐC (BẢN ĐẦY ĐỦ)

## 1. Khi nào sử dụng?

Dùng khi đã có **một ảnh infographic/poster với nội dung đã được rà soát**, cần chuyển thể sang các khổ hình khác nhau để đăng fanpage, story hoặc trình chiếu. Đây là bài toán **thích nghi bố cục (layout adaptation)**, không phải thiết kế lại nội dung hay phát triển ý tưởng mới.

**Đầu vào:**
- Ảnh gốc ở chất lượng tốt, nội dung đã được kiểm tra.
- Tỷ lệ đích cần tạo (chọn một hoặc nhiều).
- Nếu có: bản văn bản nội dung hoặc logo/ảnh gốc cần giữ chính xác, để thuận tiện khi bố trí lại.

**Đầu ra:** Mỗi tỷ lệ được chọn là **một ảnh riêng**, kèm mô tả ngắn những điều chỉnh bố cục.

## 2. PROMPT — SAO CHÉP

Bạn là nhà thiết kế truyền thông số chuyên chuyển thể infographic/poster cho nhiều nền tảng. Tôi đã đính kèm **ẢNH GỐC được kiểm tra nội dung**.

**NHIỆM VỤ:** Hãy **trực tiếp tạo ảnh từ ảnh gốc** theo các định dạng tôi chọn dưới đây, không chỉ mô tả phương án thiết kế:

| Chọn | Định dạng | Tỷ lệ | Kích thước gợi ý |
|---|---|---|---|
| [ ] | Feed dọc | 4:5 | 1080 × 1350 px |
| [ ] | Ảnh vuông | 1:1 | 1080 × 1080 px |
| [ ] | Story/reels | 9:16 | 1080 × 1920 px |
| [ ] | Slide/ảnh ngang | 16:9 | 1920 × 1080 px |

**Quy tắc giữ nguyên nội dung**
1. Giữ nguyên **tiêu đề, thông điệp, từng câu chữ, số liệu, đơn vị, ngày tháng, nguồn, hình ảnh và biểu trưng chính thức** trên ảnh gốc.
2. **Không tạo mới dữ kiện** và không tự sửa chính tả, số liệu, khẩu hiệu hoặc tên riêng nếu chưa được tôi cho phép.
3. Nếu có ảnh địa danh, chân dung, Quốc kỳ, cờ Đảng, logo hoặc biểu trưng đã được cung cấp, hãy **giữ đúng hình dạng và nhận diện**, không kéo giãn hay thay bằng hình tự sinh khác.

**Quy tắc thích nghi bố cục**
1. Được **di chuyển, sắp xếp lại các khối nội dung, thay kích thước chữ, khoảng cách và cách đặt hình** để ảnh mới hài hòa, dễ đọc.
2. Không được chỉ kéo giãn ảnh gốc cho vừa khung, không cắt mất các vùng chứa dữ kiện hoặc nguồn. Giữ các yếu tố quan trọng trong vùng nhìn thấy.
3. Với **4:5**, ưu tiên thứ bậc thông tin rõ và đọc được khi xem trên điện thoại.
4. Với **1:1**, giảm khoảng trống và sắp xếp khối hợp lý; **nếu cần rút chữ, hãy đề xuất nội dung rút gọn để tôi xác nhận trước khi tạo**, không tự lược bỏ điều kiện hoặc nguồn.
5. Với **9:16**, giữ tiêu đề, số liệu và nguồn trong vùng an toàn, tránh sát mép trên/dưới và các vị trí có thể bị giao diện ứng dụng che. Vùng an toàn phụ thuộc nền tảng; không mặc định một kích thước chính xác khi chưa có yêu cầu của kênh đăng.
6. Với **16:9**, cân nhắc bố cục ngang theo 2–3 cột hoặc chia khối; chữ phải đủ lớn khi đưa vào slide.
7. Khi nội dung dài khiến một tỷ lệ không thể vừa mà vẫn dễ đọc, hãy **thông báo hạn chế, đề xuất chia ảnh hoặc bản rút gọn**, chờ tôi quyết định thay vì tự bỏ dữ kiện.

**Cách xuất kết quả**
- Mỗi định dạng là **một tệp ảnh riêng**; không ghép cả ba/bốn phiên bản vào một ảnh duy nhất.
- Nếu công cụ không thể tạo nhiều tỷ lệ trong cùng một lần, hãy làm **lần lượt từng tỷ lệ** hoặc đề nghị tôi gửi một yêu cầu cho mỗi bản. Không nhận đã xuất đủ nếu chưa có đủ ảnh.
- Nêu **tỷ lệ và kích thước thực tế** chỉ khi có thể xác định từ tệp; không nhầm kích thước gợi ý với kích thước đã xuất.
- Sau mỗi ảnh, báo ngắn: những khối nào được chuyển vị trí; có phần nào chưa thể giữ nguyên; các chỗ cần soát lại.
- Các ảnh vẫn là **bản nháp để người biên tập kiểm tra**, không tự coi đã phê duyệt.

## 3. Lệnh thực hành nhanh

> Tôi đính kèm một infographic 4:5 đã kiểm tra nội dung. Hãy tạo **một bản story 9:16** từ ảnh này. Giữ nguyên mọi chữ, số, nguồn và logo; được sắp xếp lại bố cục để chữ lớn và nằm trong vùng an toàn, không kéo méo hình. Xuất ảnh mới và cho biết phần nào đã thay đổi. Nếu không thể giữ đủ nội dung, hãy báo trước, không tự cắt bỏ.

## 4. TỰ KIỂM TRƯỚC KHI SỬ DỤNG

- **Tỷ lệ:** Ảnh thực xuất có đúng 4:5, 1:1, 9:16 hoặc 16:9 không? Kích thước pixel thực tế có phù hợp nơi đăng không?
- **Chữ và số:** Đã đối chiếu **tất cả** chữ, số liệu, đơn vị và tên riêng với bản gốc chưa?
- **Nguồn và nhận diện:** Nguồn, chú thích, logo, cờ/biểu trưng có còn đầy đủ và đúng hình dạng không?
- **Bố cục:** Chữ đủ lớn; các hình không bị méo; không bị cắt cụt hoặc đè chồng?
- **Vùng an toàn:** Story/reels còn nội dung trọng yếu nào nằm sát mép có nguy cơ bị ứng dụng che không?

**Nguyên tắc tập huấn:** Đổi **tỷ lệ ảnh**, không tự đổi **ý nghĩa thông tin**.
