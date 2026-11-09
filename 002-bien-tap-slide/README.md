# 02 — Biên tập slide bài giảng với AI

Bộ học liệu AITrainTU dành cho cán bộ, chuyên viên biên soạn bài giảng chuyên đề và bài giới thiệu, quán triệt nghị quyết. Quy trình ưu tiên tạo bản trình chiếu hoàn chỉnh, giảm biên tập thủ công và giữ bước kiểm tra với tài liệu gốc.

## Bắt đầu từ đâu?

1. Chuẩn bị tài liệu được phép xử lý trên nền tảng AI, tên chủ đề, người nghe và thời lượng.
2. Chọn **một** trong hai prompt P01A hoặc P01B. Không cần chạy cả hai.
3. Đọc và duyệt file đề cương `.docx` trước khi tạo slide.
4. Chạy P02, chọn tông màu và tài nguyên chính thức nếu có.
5. Chạy P03, rồi tự đối chiếu các thông tin quan trọng với nguồn.
6. Dùng P04 khi cần sửa. Sau thay đổi nội dung, chạy lại phần kiểm tra liên quan của P03.

## Danh mục prompt

| Prompt | Khi nào sử dụng? | Đầu ra |
| --- | --- | --- |
| [P01A — Đề cương linh hoạt](prompts/P01A-doc-nguon-lap-de-cuong.md) | Cần sắp xếp nội dung theo người nghe và thời lượng | Đề cương Word và bảng ánh xạ sang slide |
| [P01B — Giữ đầy đủ bố cục](prompts/P01B-giu-day-du-bo-cuc.md) | Phải giữ tên, mã, thứ tự, phân cấp Phần–Chương–Mục trong phạm vi chọn | Đề cương Word, bảng kiểm kê đầy đủ đề mục và ánh xạ sang slide |
| [P02 — Tạo slide hoàn chỉnh](prompts/P02-tao-slide-hoan-chinh.md) | Sau khi duyệt đề cương | Bản trình chiếu, ưu tiên PPTX chỉnh sửa được, có ghi chú |
| [P03 — Đối chiếu, sửa lỗi](prompts/P03-doi-chieu-sua-loi.md) | Sau khi tạo slide hoặc thay đổi nội dung | Bản đã sửa và danh sách điểm cần xác minh |
| [P04 — Chỉnh sửa nhanh](prompts/P04-chinh-sua-nhanh.md) | Rút thời lượng, giảm chữ, đổi màu hoặc điều chỉnh trọng tâm | Bản trình chiếu cập nhật |

## Lựa chọn P01A hay P01B

**P01A** phù hợp khi có thể tổ chức lại nội dung để dễ trình bày. AI vẫn phải giữ đúng ý nghĩa và thông tin nguồn.

**P01B** phù hợp khi yêu cầu bao phủ đầy đủ cấu trúc của một văn bản. Người dùng chỉ định văn bản làm trục, phạm vi và độ sâu đề mục. AI không tự gộp, đổi tên, đảo thứ tự hoặc bỏ mục. Một mục có thể trải qua nhiều slide. Giữ bố cục không có nghĩa là chép nguyên văn mọi đoạn lên màn hình.

Nếu thời lượng không đủ, P01B phải nêu xung đột để người biên soạn chọn tăng thời lượng hoặc chia buổi. Không tự đưa nội dung bắt buộc vào phụ lục để coi là đã trình bày đầy đủ.

## Đề cương Word để duyệt

Hai bản P01 đều yêu cầu xuất `.docx` có thể chỉnh sửa. Đây là định dạng Word hiện đại; bộ prompt không yêu cầu `.doc` nhị phân đời cũ. File gồm yêu cầu bài trình bày, phạm vi nguồn, đề cương, bảng ánh xạ sang slide và điểm cần xác nhận. Nếu công cụ không tạo file được, dùng nội dung có cấu trúc để sao chép vào Word.

Câu lệnh sau khi duyệt:

```text
Tôi duyệt đề cương trong file đính kèm. Hãy dùng đúng phiên bản này để thực hiện P02. Chế độ cấu trúc: [P01A/P01B]. Phong cách màu: [A/B/C/D]. Tài nguyên chính thức: [không dùng/tệp đính kèm].
```

Nếu sửa đề cương ngoài cuộc trò chuyện, đính kèm lại bản đã sửa. Nếu chuyển công cụ, chuyển cả tài liệu nguồn, đề cương đã duyệt, lựa chọn thiết kế và yêu cầu đầu ra.

## Tông màu và tài nguyên cho slide công tác Đảng

| Lựa chọn | Cách sử dụng |
| --- | --- |
| A — Đỏ trang trọng | Đỏ đậm, vàng nhấn, nền trắng ngà. Có thể dùng bìa đỏ đậm với chữ trắng |
| B — Nền sáng, nhấn đỏ | Mặc định. Nền trắng, tiêu đề đỏ, chữ sẫm, vàng nhấn ít |
| C — Theo mẫu cơ quan | Ưu tiên đúng mẫu, phông và vị trí biểu trưng đính kèm |
| D — Tùy chọn | Người dùng khai báo màu nền, tiêu đề, chữ và điểm nhấn |

Các bảng màu A/B là **gợi ý thiết kế**, không phải quy chuẩn nhận diện chính thức. Chọn tông đỏ–vàng không đồng nghĩa với tự động thêm cờ hoặc biểu trưng. Chỉ dùng tài nguyên chuẩn được cung cấp hoặc nguồn chính thức đã xác minh; không dùng AI tự sinh cờ, búa liềm, con dấu hoặc biểu trưng thay thế. Nếu chưa có tài nguyên, vẫn có thể tạo slide bằng màu sắc phù hợp.

## Học liệu và thực hành

- [Slide giảng dạy, phiên bản 2.0](slides/AITrainTU_Soan_slide_bai_giang_voi_AI_v2.pptx)
- [Bài thực hành và tiêu chí kiểm tra](BAI_THUC_HANH.md)

Slide có ghi chú thuyết trình và prompt đầy đủ. Để sao chép prompt, ưu tiên các file Markdown trong thư mục `prompts` vì dễ đọc và cập nhật hơn phần Notes.

## Trách nhiệm kiểm tra

Chỉ sử dụng tài liệu được phép xử lý trên nền tảng đã chọn. Kiểm tra lại số liệu, chỉ tiêu, thời hạn, chủ thể và trách nhiệm thực hiện. Việc AI tự rà soát không thay thế người biên soạn duyệt nội dung. Khả năng tạo Word, PPTX, xem bố cục và thêm Notes tùy công cụ; kiểm tra đầu ra thực tế trước khi dùng trong lớp.
