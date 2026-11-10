# 003 — BIÊN TẬP VIDEO THỰC CHIẾN VỚI AI

**Mục tiêu:** Biến **video/ảnh/âm thanh đã có** thành một video ngắn gọn, dễ xem, phụ đề rõ và xuất được MP4. AI hỗ trợ **phân tích, chọn đoạn, viết lời dẫn, phụ đề và hướng dẫn thao tác**; thao tác cắt ghép được thực hiện trong phần mềm dựng nếu AI không có công cụ chỉnh sửa video.

**Không bắt buộc tạo clip bằng AI.** Không cần dùng một tài liệu lịch sử hay địa phương cụ thể. Học viên có thể dùng video tự quay, bản ghi bài hướng dẫn, clip giới thiệu hoạt động hoặc ảnh được phép sử dụng.

## Chọn prompt theo vấn đề đang gặp

| Tôi đang cần | Prompt | Kết quả |
|---|---|---|
| Có video thô, chưa biết giữ cảnh nào | [P01 – Phân tích và chọn cảnh](01-Prompts/P01-PhanTichVideoTho.md) | Danh sách cảnh và lỗi cần sửa |
| Muốn rút video dài thành video ngắn | [P02 – Rút gọn và tạo highlight](01-Prompts/P02-RutNganVideo.md) | Danh sách đoạn giữ/bỏ theo thời điểm |
| Có nhiều clip, muốn ghép thành một câu chuyện | [P03 – Sắp xếp và cắt ghép](01-Prompts/P03-CatGhepVideo.md) | Timeline biên tập |
| Cần chữ giới thiệu, phụ đề | [P04 – Chữ và phụ đề](01-Prompts/P04-TieuDeVaPhuDe.md) | Tiêu đề, caption, SRT dự thảo |
| Tiếng nhỏ, ồn hoặc nhạc quá lớn | [P05 – Âm thanh và lời đọc](01-Prompts/P05-AmThanhLoiDoc.md) | Danh sách lỗi âm và thao tác khắc phục |
| Muốn thêm ảnh, B-roll, chú thích | [P06 – Hình chèn và chuyển cảnh](01-Prompts/P06-ChenAnhBroll.md) | Shotlist lớp phủ/B-roll |
| Cần Reels, video ngang và xuất MP4 | [P07 – Đổi tỷ lệ và xuất](01-Prompts/P07-DoiTyLeXuatMP4.md) | Cài đặt xuất và kế hoạch tái bố cục |
| Muốn kiểm tra video trước khi đăng | [P08 – Kiểm tra video cuối](01-Prompts/P08-SoatVideoCuoi.md) | Bảng lỗi theo mốc thời gian |

**Bạn không phải chạy cả 8 prompt.** Ví dụ, khi đã có video quay thô: P01 → P02 hoặc P03 → P04 → P07 → P08. Nếu chỉ cần sửa phụ đề, dùng ngay P04; nếu chỉ cần đổi khổ, dùng P07.

## Một buổi thực hành ưu tiên biên tập, không ưu tiên tạo video mới

- [TH01 — Cắt ghép clip đã quay, làm video 45–60 giây](02-BaiThucHanh/TH01-CatGhepVideoTuQuay.md): bài khởi động, dự kiến 45–60 phút.
- [TH02 — Rút video dài thành clip ngắn](02-BaiThucHanh/TH02-RutVideoDaiThanhReels.md): bài ứng dụng, dự kiến 40–60 phút.
- [Hướng dẫn thao tác trên CapCut Desktop, thay thế Clipchamp](03-MauVaHuongDan/HuongDan_CapCut_Clipchamp.md).
- [Bảng nguồn/video thô giả lập](03-MauVaHuongDan/MauDanhSachCanhVaLoi.md) và [Checklist trước trình duyệt](03-MauVaHuongDan/ChecklistVideo.md).

## Quy trình biên tập 6 bước

1. **Nhập tệp:** chọn video/ảnh/nhạc được phép dùng; xác định đối tượng và thông điệp.
2. **Chọn cảnh:** xem hết video thô, đánh dấu các đoạn nên giữ và cần bỏ.
3. **Cắt ghép:** đưa clip vào timeline, rút ngắn, sắp xếp và chỉnh nhịp.
4. **Bổ sung:** tiêu đề, chữ trên màn hình, phụ đề, hình chèn, âm thanh.
5. **Xuất tệp:** MP4, 9:16 cho video dọc hoặc 16:9 cho trình chiếu (chọn theo kênh thực tế).
6. **Kiểm:** xem cả video có tiếng và tắt tiếng, đối chiếu dữ kiện và quyền sử dụng, sửa rồi trình duyệt.

> **Lưu ý an toàn:** Không đưa video nội bộ chưa được phép, hình/tiếng của người khác thiếu quyền, dữ liệu cá nhân, tài liệu mật lên AI công cộng. Không tự cắt phát biểu làm đảo ngược ngữ cảnh. Video đã dựng là **bản nháp**, không có nghĩa đã được phê duyệt.

## Tài liệu tham khảo công cụ

- CapCut Desktop: https://www.capcut.com/resource/how-to-use-capcut-on-pc
- CapCut thao tác cắt clip: https://www.capcut.com/resource/split-video-into-parts
- Microsoft Clipchamp: https://support.microsoft.com/en-us/clipchamp/video-editing-features

*Giao diện và quyền sử dụng tính năng có thể thay đổi theo phiên bản, nền tảng và tài khoản. Không dùng prompt để thay thế thao tác dựng khi công cụ AI không có quyền chỉnh tệp.*
