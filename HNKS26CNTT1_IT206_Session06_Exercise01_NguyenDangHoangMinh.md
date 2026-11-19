# Bước 1 : Phân tích lỗi

- Prompt cũ chỉ yêu cầu “ngắn gọn”, chưa quy định số ý, độ dài hay cách trình bày. Vì đề bài chưa cung cấp câu trả lời cũ của AI, ba phần thừa dưới đây là ví dụ minh họa.

|Phần thừa|Ví dụ|Lý do nên bỏ|
|-|-|-|
|Lời chào xã giao|“Chào bạn! Rất vui được hỗ trợ bạn.”|Không cung cấp kiến thức về hai khái niệm.|
|Câu dẫn nhắc lại đề|“Sau đây, mình sẽ giải thích hai nội dung mà bạn vừa hỏi.”|Lặp lại yêu cầu trước khi trả lời.|
|Lời kết mời hỏi thêm|“Nếu bạn cần thêm ví dụ, hãy cho mình biết nhé!”|Không cần thiết khi dán vào báo cáo.|
# Bước 2 : Viết Prompt tối ưu
## Prompt 
```
Giải thích cho sinh viên năm nhất hai khái niệm “Feynman Prompt gia sư” và “Rubric chấm bài tự động”.

Bắt buộc trả lời bằng đúng 2 gạch đầu dòng theo thứ tự trên. Mỗi gạch bắt đầu bằng tên khái niệm in đậm, sau đó là một câu tối đa 30 từ mô tả cách hoạt động.

Bắt đầu ngay bằng gạch đầu dòng đầu tiên. Không viết lời chào, câu dẫn, tiêu đề, lời kết hoặc lời mời hỏi thêm.
```
## Kết quả AI trả lại 
```
Feynman Prompt gia sư : Yêu cầu bạn giải thích kiến thức bằng ngôn ngữ đơn giản như dạy người mới, rồi chỉ ra chỗ hổng hiểu biết để bạn tự lấp đầy.
    
Rubric chấm bài tự động : Áp dụng thang tiêu chí có sẵn để AI đánh giá bài làm, cho điểm nhanh và gợi ý cách cải thiện theo từng tiêu chuẩn.
```
