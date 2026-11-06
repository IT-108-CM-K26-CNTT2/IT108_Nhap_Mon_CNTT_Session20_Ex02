# Bài 2 : Đánh giá chất lượng câu trả lời khi xử lý lỗi lập trình
## 3. Yêu cầu đầu ra

### Phân tích ưu/nhược điểm của từng câu trả lời dựa trên 3 tiêu chí: Tích xanh, Điểm Vote và Thời gian đăng.

| | Ưu điểm | Nhược điểm |
|---|---|---|
| **Tích xanh** | Dễ nhận biết, tăng tin cậy | Có thể bị mua, không đảm bảo nội dung đúng |
| **Điểm Vote** | Phản ánh cộng đồng, đẩy nội dung hay lên | Dễ vote ảo, bài đăng muộn bị chìm |
| **Thời gian đăng** | Thông tin mới, công bằng | Bài hay dễ bị trôi, dễ spam |

### Lựa chọn câu trả lời bạn sẽ áp dụng và lập luận tại sao (lưu ý bẫy về phiên bản phần mềm đã cũ).
-Mình sẽ chọn câu trả lời khớp với phiên bản phần mềm đang dùng, rồi mới xét vote, và chỉ coi tích xanh là tín hiệu phụ. Thời gian đăng không phải tiêu chí chọn, mà là công cụ để kiểm tra độ cũ.

** Vì sao cả ba tiêu chí đều có bẫy phiên bản:**

- **Tích xanh**: Người hỏi tích xanh tại thời điểm họ hỏi. Sau vài năm, thư viện hoặc framework có thể đã đổi API, nhưng dấu tích vẫn nằm đó và dễ khiến bạn tin mù quáng.
- **Điểm vote**: Câu trả lời cũ có nhiều thời gian để tích lũy vote, nên thường vượt xa câu mới dù câu mới đúng với phiên bản hiện tại. Vote cao chỉ cho biết nó từng hữu ích, không đảm bảo còn đúng.
- **Thời gian đăng**: Mới không đồng nghĩa với đúng, vì câu mới có thể chưa được ai kiểm chứng. Nhưng ngày đăng giúp bạn đối chiếu với thời điểm phiên bản của mình ra đời.
