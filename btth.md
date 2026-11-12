# [BTTH] Cẩm nang sử dụng AI hiệu quả cho tân sinh viên
**Yêu cầu thực hiện chi tiết**

Sử dụng kỹ thuật chia nhỏ prompt (Prompt Chaining) để viết cẩm nang theo từng phần:

\- Phần 1: Cách AI đoán từ (LLM hoạt động thế nào).

- LLM (Large Language Model) là mô hình ngôn ngữ lớn khi bạn nhập câu hỏi nó sẽ sử dụng xác suất để đoán từ kế tiếp theo đúng với ngữ cảnh phía trước và chọn từ có xác suất cao nhất tạo thành câu trả lời

\- Phần 2: 3 cách nhận diện ảo giác của AI.

- 3 cách nhận diện ảo giác của AI:
   - phải kiểm chứng nhiều Model AI khác nhau 
   - ràng buộc trong một khung dữ liệu như file bài 
   - phải đối chiếu dữ liệu một cách kĩ càng 

\- Phần 3: Cấu trúc prompt mẫu tối ưu bằng khung CREATE.

- context: cung cấp bối cảnh 
- role: cung cấp vai trò cho AI vd như bạn là thầy giáo 
- explicit: nêu yêu cầu cụ thể vd như chấm bài
- audience: xác định đối tượng đọc
- tone: giọng văn vd như thầy cô giảng dạy
- expected output: yêu cầu kết quả đầu ra 