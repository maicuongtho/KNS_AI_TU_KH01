# Thư viện prompt AI — Sáng tạo ảnh, infographic và poster

**AITrainTU · Chuyên đề 002 — Kỹ năng ứng dụng AI trong thiết kế sản phẩm tuyên truyền**

Bộ **9 prompt thực hành (P01–P09)** giúp chuyển tài liệu, dữ kiện và ảnh tham khảo thành sản phẩm truyền thông trực quan; sau đó chỉnh sửa, chuyển tỷ lệ và kiểm tra trước khi trình duyệt. Dành cho cán bộ, công chức, báo cáo viên và người biên tập nội dung số.

> **Bắt đầu nhanh:** Mở một tệp `*-ban-ngan-gon.md` trong bảng dưới đây, sao chép phần **PROMPT — SAO CHÉP**, thay thông tin trong dấu `[ ]`, đính kèm dữ liệu/ảnh cần thiết và gửi đến công cụ AI có hỗ trợ tạo ảnh. Sản phẩm AI tạo ra cần được kiểm tra trước khi sử dụng chính thức.

## 1. Chọn prompt theo nhu cầu

| Mã | Khi nào dùng? | Bản thực hành | Bản đầy đủ |
|---|---|---|---|
| **P01** | Có PDF, muốn tạo ngay infographic | [Mở P01](prompts/P01-TỪ%20PDF%20ĐẾN%20ẢNH%20INFOGRAPHIC%20TRONG%20MỘT%20LỆNH.md) | [Chi tiết](prompts/P01-ver2-TỪ%20PDF%20ĐẾN%20ẢNH%20INFOGRAPHIC%20TRONG%20MỘT%20LỆNH.md) |
| **P02** | Chưa có ý tưởng, muốn AI đề xuất **3 concept** để chọn | [Mở P02](prompts/P02-%20AI%20LÀ%20CREATIVE%20DIRECTOR_%20ĐỀ%20XUẤT%203%20CONCEPT%20THIẾT%20KẾ.md) | [Chi tiết](prompts/P02-ver2-%20AI%20LÀ%20CREATIVE%20DIRECTOR_%20ĐỀ%20XUẤT%203%20CONCEPT%20THIẾT%20KẾ.md) |
| **P03** | Có ảnh mẫu; muốn học cách bố trí rồi tạo ảnh **mới** với nội dung của mình | [Mở P03](prompts/P03-THIẾT%20KẾ%20NGƯỢC%20TỪ%20ẢNH%20THAM%20KHẢO.md) | [Chi tiết](prompts/P03-ver2-THIẾT%20KẾ%20NGƯỢC%20TỪ%20ẢNH%20THAM%20KHẢO.md) |
| **P04** | Trình bày các **mốc lịch sử** thành timeline có nguồn | [Mở P04](prompts/P04-TẠO%20INFOGRAPHIC%20TIMELINE%20LỊCH%20SỬ%20CÓ%20NGUỒN%20.md) | [Chi tiết](prompts/P04-ver2-TẠO%20INFOGRAPHIC%20TIMELINE%20LỊCH%20SỬ%20CÓ%20NGUỒN.md) |
| **P05** | Trực quan hóa **số liệu báo cáo, thống kê, kết quả** | [Mở P05](prompts/P05-Tạo%20infographic%20số%20liệu%20có%20nguồn.md) | [Chi tiết](prompts/P05-ver2-Tạo%20infographic%20số%20liệu%20có%20nguồn%20.md) |
| **P06** | Tạo **poster cổ động/kỷ niệm**: một thông điệp, ít chữ, hình ảnh nổi bật | [Mở P06](prompts/P06-Tạo%20poster%20cổ%20động%20_%20kỷ%20niệm%20bằng%20AI.md) | [Chi tiết](prompts/P06-ver2-%20Tạo%20poster%20cổ%20động%20_%20kỷ%20niệm%20bằng%20AI.md) |
| **P07** | Ảnh gần đạt; cần **sửa đúng chữ, màu hoặc chi tiết cụ thể** | [Mở P07](prompts/P07-CHỈNH%20SỬA%20ẢNH%20ĐÃ%20TẠO%20THEO%20YÊU%20CẦU.md) | [Chi tiết](prompts/P07-ver2%20-%20CHỈNH%20SỬA%20ẢNH%20ĐÃ%20TẠO%20THEO%20YÊU%20CẦU.md) |
| **P08** | Chuyển một ảnh sang **4:5, 1:1, 9:16 hoặc 16:9** | [Mở P08](prompts/P08-%20TẠO%20CÁC%20TỶ%20LỆ%20ẢNH%20TỪ%20BẢN%20GỐC.md) | [Chi tiết](prompts/P08-ver2-%20TẠO%20CÁC%20TỶ%20LỆ%20ẢNH%20TỪ%20BẢN%20GỐC.md) |
| **P09** | Kiểm tra chữ, dữ kiện, hình ảnh, nguồn trước khi trình duyệt | [Mở P09](prompts/P09-KIỂM%20TRA%20INFOGRAPHIC_POSTER%20CUỐI%20TRƯỚC%20KHI%20TRÌNH%20DUYỆT.md) | [Chi tiết](prompts/P09-ver2-KIỂM%20TRA%20INFOGRAPHIC_POSTER%20CUỐI%20TRƯỚC%20KHI%20TRÌNH%20DUYỆT.md) |

**Hai mức sử dụng:** Bản **ngắn gọn** dành cho học viên sao chép, thực hành ngay; bản **đầy đủ** để hiểu các điều kiện đầu vào, cách kiểm soát chất lượng và tình huống khó.

## 2. Quy trình thực hành

```text
CHUẨN BỊ NGUỒN NỘI DUNG / DỮ KIỆN / ẢNH
                  │
                  ▼
   CHỌN CÁCH BẮT ĐẦU (không cần chạy cả ba)
   P01: PDF → infographic ngay
   P02: AI gợi ý 3 concept → chọn 1
   P03: Phân tích ảnh mẫu → tạo thiết kế mới
                  │
                  ▼
      TẠO SẢN PHẨM THEO MỤC TIÊU
      P04: Timeline lịch sử
      P05: Infographic số liệu
      P06: Poster cổ động/kỷ niệm
      (hoặc dùng trực tiếp P01/P03)
                  │
                  ▼
       P07: CHỈNH SỬA NẾU CẦN
                  │
                  ▼
       P08: ĐỔI TỶ LỆ NẾU CẦN
                  │
                  ▼
       P09: KIỂM TRA ẢNH CUỐI
                  │
                  ▼
      NGƯỜI PHỤ TRÁCH TRÌNH DUYỆT
```

**Lưu ý:** P02 chỉ **đề xuất phương án**, chưa tạo ảnh ở bước đầu; sau khi chọn concept, yêu cầu AI tạo ảnh trực tiếp. P07 và P08 có thể làm thay đổi chữ hoặc bố cục ngoài ý muốn, vì vậy **luôn kiểm tra lại phiên bản ảnh cuối bằng P09**.

## 3. Năm thông tin nên chuẩn bị trước khi dùng AI

1. **Mục tiêu:** Ảnh nhằm giải thích điều gì hoặc nhấn mạnh thông điệp nào?
2. **Đối tượng:** Cán bộ, đảng viên, đoàn viên, người dân hay nhóm người xem khác?
3. **Nội dung và nguồn:** Văn bản/PDF/bảng số liệu đã được phép sử dụng; ngày tháng, đơn vị, kỳ thống kê cần giữ chính xác.
4. **Hình thức và đầu ra:** Infographic, timeline, poster; kênh sử dụng và tỷ lệ (4:5, 1:1, 9:16, 16:9...).
5. **Tài nguyên hình ảnh (nếu có):** Ảnh địa danh, ảnh mẫu tham khảo, logo, cờ, biểu trưng; nêu rõ vai trò từng tệp.

## 4. Ba bài thực hành gợi ý

| Bài | Nhiệm vụ | Lộ trình prompt | Sản phẩm cần kiểm tra |
|---|---|---|---|
| **01 — Quy trình** | Tạo infographic “5 bước chuẩn bị và tổ chức hội nghị trực tuyến” từ nội dung cho sẵn | P01 (nếu có PDF) hoặc P02 → tạo ảnh → P07 → P09 | Đúng thứ tự bước, chữ tiếng Việt, mũi tên và thông điệp |
| **02 — Dòng thời gian** | Tạo timeline một sự kiện hoặc quá trình lịch sử từ tài liệu đã xác minh | P04 → P07 → P09 | Đúng mốc, thứ tự thời gian, địa danh và trang nguồn |
| **03 — Truyền thông đa định dạng** | Tạo poster hoặc infographic rồi chuyển sang story/slide | P06 hoặc P05 → P08 → P09 | Không mất chữ, số liệu, nguồn và không làm biến dạng hình |

Trong buổi học, **chỉ cần hoàn thành một sản phẩm đúng và kiểm tra được nguồn**; không bắt buộc sử dụng cả 9 prompt cho một bài.

## 5. Slide và thư mục tài liệu

- [PowerPoint — Bộ slide 16 trang (P01–P09)](slides/Slide_Infographic_Day_du_P01_den_P09.pptx)
- [Thư mục nguồn trên Google Drive](https://drive.google.com/drive/folders/13PhATbkTt10WLx_XFLlCocZvu__zSNy_) — tài liệu đối chiếu các phiên bản đã chia sẻ.

```text
thu-vien-prompt-infographic/
├── README.md
├── prompts/
│   ├── P01-ban-ngan-gon.md
│   ├── P01-ban-day-du.md
│   ├── ...
│   ├── P09-ban-ngan-gon.md
│   └── P09-ban-day-du.md
└── slides/
    └── Slide_Infographic_Day_du_P01_den_P09.pptx
```

Các đường dẫn trong README là **đường dẫn tương đối**: khi tải toàn bộ thư mục lên GitHub với cấu trúc trên, có thể mở prompt trực tiếp bằng cách nhấp liên kết trong bảng.

## 6. Nguyên tắc sử dụng và kiểm tra

- **Nguồn đáng tin cậy:** Không tự tạo ngày tháng, sự kiện, số liệu, trích dẫn; giữ đúng từ chỉ mức độ như “ước”, “hơn”, “gần”, cũng như đơn vị và kỳ báo cáo.
- **Kiểm tra ảnh thực tế:** Đọc lại từng chữ/số xuất hiện trên ảnh, kiểm tỷ lệ biểu đồ và đối chiếu dữ liệu gốc. AI có thể tạo ảnh đẹp nhưng vẫn sai chữ hoặc số.
- **Sử dụng hình ảnh:** Nếu cần thể hiện chính xác địa danh, chân dung, logo, cờ hoặc biểu trưng, ưu tiên tệp được cung cấp hợp lệ; kiểm tra kết quả không bị biến dạng. Không giới thiệu hình tái hiện bằng AI như ảnh tư liệu lịch sử thật.
- **An toàn thông tin:** Không đưa lên dịch vụ AI công cộng hoặc kho GitHub công khai tài liệu mật, dữ liệu nội bộ hạn chế, thông tin cá nhân hoặc tài nguyên chưa được phép công bố. Tuân thủ quy định của cơ quan và hệ thống thông tin của Đảng.
- **Phê duyệt:** Các ảnh mẫu và kết quả AI là **bản nháp**. P09 chỉ hỗ trợ kiểm tra, **không thay thế người biên tập và cấp có thẩm quyền phê duyệt**.

## 7. Cập nhật học liệu

Khi sửa một prompt, nên cập nhật **cả bản ngắn gọn và bản đầy đủ** cùng mã Pxx. Giữ tên tệp ổn định để các liên kết từ README và slide không bị hỏng. Với ảnh/bảng dữ liệu bổ sung, chỉ đưa vào kho khi có quyền chia sẻ.

---

*Học liệu phục vụ tập huấn kỹ năng ứng dụng AI trong sáng tạo ảnh và truyền thông số. Nội dung có thể điều chỉnh theo nhiệm vụ, đối tượng người học và quy định của đơn vị.*
