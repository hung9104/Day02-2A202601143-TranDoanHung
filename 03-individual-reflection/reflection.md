# 03 — Individual Reflection

**Họ và tên:** Trần Doãn Hưng  
**Mã học viên:** 2A202601143

## Đóng góp trong nhóm

| Hoạt động | Tôi đã làm gì? | Kết quả |
|---|---|---|
| Scan cá nhân | Scan 7 vấn đề, chọn các vấn đề 2, 6 và 7 làm Top 3 | Có ba Problem Card với actor, workflow và bottleneck rõ |
| Pitch | Pitch vấn đề 7: giáo viên mất khoảng 10–20 phút tìm quy định trên nhiều kênh | Vấn đề được đưa vào danh sách candidates và liên quan trực tiếp đến PolicyMate |
| Challenge | Hỏi liệu tìm đúng file và có citation đã đủ chưa nếu văn bản hết hiệu lực | Nhóm tách việc tìm đúng nguồn, citation đúng và phiên bản còn hiệu lực |
| Workflow | Góp ý bước kiểm tra nguồn, hiệu lực, quyền truy cập và fallback | Future workflow có Rule, AI hỗ trợ và người thật kiểm tra |
| Problem Statement | Làm rõ boundary và các giả định về metadata, phiên bản văn bản | AI không được tự kết luận khi thiếu nguồn hoặc không rõ hiệu lực |
| Rule / Workflow / Agent | Lập luận chọn Workflow và quyết định `Not Yet` | Nhóm chưa chọn Agent hay Go vì chưa có validation, baseline và dữ liệu đủ tin cậy |

## Bảng dùng AI trong reflection

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai/hời hợt ở đâu? | Tôi sửa gì |
|---|---|---|---|---|
| Problem Card | Đưa Top 3 problems về đúng template | Giúp đủ actor, bottleneck, metric và alternative | Gợi ý một số target chưa có dữ liệu | Ghi rõ đâu là quan sát, đâu là target cần kiểm chứng |
| Workflow | Chuyển mô tả thành current/future workflow | Làm rõ vị trí của Rule, AI và con người | Có xu hướng tự động hóa quá nhiều | Bổ sung human review và fallback |
| Research | Tìm pattern về citation, phân quyền và version control | Giúp thấy metadata phải được xử lý trước AI | Benchmark bên ngoài không chứng minh kết quả của PolicyMate | Chỉ dùng để tham khảo, không xem là validation |
| Problem Statement | Phản biện metric, boundary và mức giải pháp | Chỉ ra citation đúng chưa chắc văn bản còn hiệu lực | Có thể đề xuất Agent quá sớm | Chọn Workflow và giữ quyết định `Not Yet` |

## Bài học

- Problem tốt cần actor, workflow, bottleneck và metric rõ, không cần phải là bài dùng AI nhiều nhất.
- Citation đúng chưa đủ; văn bản còn phải đúng phiên bản và còn hiệu lực.
- Process fix và Rule phù hợp với metadata, hiệu lực và phân quyền; AI chỉ hỗ trợ tìm và draft câu trả lời.
- Workflow phù hợp hơn Agent vì các bước đã rõ và vẫn cần người thật kiểm tra.
- Con số 10–20 phút mới là một quan sát ban đầu; target dưới 5 phút và correctness 85% vẫn cần validation.

Nếu làm lại:

```text
Tôi sẽ phỏng vấn thêm 2–3 giáo viên, đo ít nhất 10 tác vụ tra cứu
và audit một mẫu văn bản trước khi chốt baseline, metric và quyết định Go.
```

> Tôi cần kiểm tra lại phần pitch và challenge để bảo đảm đúng với những việc mình thực sự đã làm trước khi nộp.
