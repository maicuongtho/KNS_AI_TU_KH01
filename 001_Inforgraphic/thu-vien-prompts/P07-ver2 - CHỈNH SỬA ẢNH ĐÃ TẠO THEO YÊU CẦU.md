# P07 — CHỈNH SỬA ẢNH ĐÃ TẠO THEO YÊU CẦU

## 1\. Mục đích sử dụng

**Dùng khi:** Ảnh infographic/poster đã gần hoàn thiện nhưng cần chỉnh một số chi tiết như chữ, số liệu, màu sắc, cỡ chữ, căn lề, khoảng cách hoặc bổ sung/xóa một thành phần.

**Không dùng khi:** Cần thay hoàn toàn bố cục, thông điệp hoặc phong cách. Trường hợp đó nên yêu cầu thiết kế lại một phiên bản mới.

**Đầu vào:**

- Ảnh gốc (PNG/JPG hoặc hình được đính kèm trong cuộc trò chuyện).  
- Mô tả rõ vị trí cần sửa: ví dụ *khối thứ hai bên phải*, *tiêu đề ở đầu ảnh*, *dòng nguồn ở chân ảnh*.  
- Nội dung cũ và nội dung mới **nguyên văn**, nhất là khi sửa chữ hoặc số liệu.  
- Ảnh, biểu trưng, logo muốn bổ sung **nếu có**; sử dụng theo quyền được cấp.

**Đầu ra:** Một ảnh đã chỉnh sửa, giữ nguyên tối đa các phần không liên quan, kèm danh sách thay đổi ngắn.

## 2\. PROMPT — SAO CHÉP

Tôi đính kèm **ảnh infographic/poster hiện tại**. Bạn là nhà thiết kế đồ họa có kinh nghiệm hiệu chỉnh ảnh AI.

**NHIỆM VỤ: HÃY TRỰC TIẾP CHỈNH SỬA ẢNH GỐC** theo đúng các chỉ dẫn dưới đây. Không chỉ viết hướng dẫn, không chủ động tạo một thiết kế hoàn toàn mới.

### A. Những yếu tố phải giữ nguyên

- Bố cục tổng thể, thứ tự thông tin, phong cách thiết kế và hình ảnh chủ đạo.  
- Nền và màu sắc ở các vùng không yêu cầu sửa.  
- Mọi câu chữ, số liệu, tên riêng, mốc thời gian và đơn vị **không nằm trong danh sách cần sửa**.  
- Tỷ lệ khung hình và chất lượng hiển thị, trừ khi có yêu cầu thay đổi riêng.

Nếu nội dung thay thế dài hơn, **được phép điều chỉnh nhẹ vùng chữ liên quan** (cỡ chữ, xuống dòng, khoảng cách hoặc chiều rộng khung) để tránh tràn chữ, nhưng không làm thay đổi bố cục tổng thể hoặc các vùng không liên quan.

### B. Chỉ thực hiện những thay đổi sau

1. **Sửa nội dung:** Tại **\[VỊ TRÍ CỤ THỂ\]**, thay chính xác **“\[CHỮ/SỐ CŨ\]”** bằng **“\[CHỮ/SỐ MỚI\]”**.  
2. **Sửa trình bày (nếu có):** **\[MÀU / CỠ CHỮ / CĂN LỀ / KHOẢNG CÁCH / ĐỘ TƯƠNG PHẢN\]** tại **\[VỊ TRÍ\]**.  
3. **Sửa thành phần hình ảnh (nếu có):** **\[XÓA / THÊM / THAY THẾ\]** chi tiết **\[MÔ TẢ\]** tại **\[VỊ TRÍ\]**. Nếu thêm ảnh, logo hoặc biểu trưng cụ thể, chỉ dùng **tệp đính kèm được phép sử dụng**.

**Nếu một mục không áp dụng, bỏ qua mục đó. Không tự sáng tác thay đổi khác.**

### C. Yêu cầu chất lượng

- Tiếng Việt đúng dấu; kiểm kỹ tên riêng, số liệu, ngày tháng, đơn vị, dấu câu và các từ thể hiện mức độ như “ước”, “hơn”, “gần”.  
- Không tự sửa các số liệu khác, không thêm logo, cờ, phù hiệu, sự kiện, người hoặc phát biểu nếu chưa được yêu cầu.  
- Không làm hình bị kéo méo, nhòe, vỡ chữ hoặc biến dạng biểu trưng đã cung cấp.  
- Giữ nguyên các vùng không liên quan trong khả năng của công cụ. Không tự ý tái thiết kế toàn bộ ảnh.  
- Nếu hệ thống không bảo đảm chỉnh sửa chính xác từng vùng hoặc giữ nguyên toàn bộ chi tiết, **nêu rõ giới hạn**; có thể đề nghị sửa bằng lớp chữ trong công cụ biên tập ảnh, thay vì khẳng định đã giữ nguyên tuyệt đối.

### D. Đầu ra

1. **Xuất trực tiếp ảnh đã chỉnh sửa** nếu công cụ hỗ trợ.  
2. Nêu ngắn gọn: **vùng đã sửa → nội dung thay đổi**.  
3. Cho biết điểm nào còn cần người dùng kiểm tra lại. Không tự tuyên bố sản phẩm đã được phê duyệt.

## 3\. Ví dụ lệnh nhanh

> Giữ nguyên bố cục, màu nền, các mốc và hình chính. Chỉ sửa chữ ở khối số liệu thứ hai từ “Doanh thu du lịch năm 2026 đạt 67.950 tỷ” thành “Trong 9 tháng năm 2026, doanh thu du lịch ước đạt hơn 67.950 tỷ đồng”. Cho phép giãn nhẹ dòng chữ ở khối này để không bị tràn. Không sửa các vị trí khác. Hãy xuất ảnh sau khi chỉnh sửa.

**Lưu ý:** Giá trị trong ví dụ chỉ nhằm minh họa câu lệnh chỉnh sửa, không được xem là số liệu chính thức đã kiểm chứng.

## 4\. Tự kiểm sau khi AI trả ảnh

- **Đối chiếu trước/sau:** Vị trí được yêu cầu đã sửa đúng chưa? Có vùng ngoài phạm vi bị thay đổi không?  
- **Kiểm từng ký tự:** Dấu tiếng Việt, tên riêng, số liệu, đơn vị, kỳ thống kê và câu chữ mới đã chính xác chưa?  
- **Kiểm trình bày:** Có tràn chữ, méo hình, sai màu, nhòe hoặc mất nguồn không?  
- **Nếu xuất hiện lỗi mới:** Quay lại ảnh gốc hoặc phiên bản đúng nhất để chỉnh lại. Không liên tục sửa trên một ảnh đã phát sinh lỗi dây chuyền.

## 5\. Gợi ý&nbsp;&nbsp;

Đối với bài tập 5–10 phút, chỉ yêu cầu sửa **một lỗi chữ và một lỗi bố cục nhỏ** trên ảnh có sẵn. Cho học viên nộp ảnh trước/sau và tự mô tả các vùng đã thay đổi. Phần hướng dẫn ngắn gọn chỉ cần dùng bản `P07-ban-ngan-gon.md`.