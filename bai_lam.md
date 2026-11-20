# [Bài thực hành 4] Sử dụng Feynman Prompt để học kiến thức lập trình
## Vấn đề:
Bạn là sinh viên ngành Công nghệ thông tin vừa học xong bài OOP (Lập trình hướng đối tượng).

Bạn đã ghi nhớ các khái niệm:

- Class.

- Object.

- Attribute.

- Method.

- Constructor.

Tuy nhiên, bạn chưa chắc mình đã thực sự hiểu bản chất của các khái niệm này hay chỉ đang học thuộc định nghĩa.

Bạn quyết định sử dụng AI làm gia sư để kiểm tra mức độ hiểu bài.
## Yêu cầu:
- Prompt hoàn chỉnh để thiết lập AI làm gia sư.

- Bản ghi cuộc hội thoại tối thiểu 5 câu hỏi – trả lời.

- Bảng đánh giá mức độ hiểu từng khái niệm.

- Một ví dụ minh họa mối quan hệ giữa Class và Object trong thực tế.

- Tự viết lại phần giải thích OOP sau khi hoàn thành buổi học.
## Cách làm:
# [Bài thực hành 4] Sử dụng Feynman Prompt để học kiến thức lập trình

* **Môn học:** Kỹ Năng Promting với AI (`IT206-K26` – Buổi 7)
* **Chủ đề lựa chọn:** Lập trình hướng đối tượng (OOP) trong **Java**

---

## 1. Prompt hoàn chỉnh thiết lập AI làm gia sư

```markdown

Bạn là một giảng viên và gia sư lập trình hướng đối tượng (OOP) trong ngôn ngữ Java giàu kinh nghiệm, kiên nhẫn và áp dụng phương pháp học tập Feynman (học thông qua việc giải thích lại bằng ngôn ngữ đơn giản).
Tôi là sinh viên ngành Công nghệ thông tin vừa học lý thuyết về 5 khái niệm cơ bản của OOP trong Java: Class, Object, Attribute, Method và Constructor. Tôi muốn bạn kiểm tra xem tôi đã thực sự hiểu bản chất hay chỉ đang học thuộc lòng định nghĩa.

# RÀNG BUỘC 
1. TUYỆT ĐỐI KHÔNG giải thích toàn bộ kiến thức ngay từ đầu.
2. Chỉ đặt TỪNG CÂU HỎI MỘT và chờ tôi trả lời rồi mới tiếp tục.
3. Sau mỗi câu trả lời của tôi, hãy đánh giá mức độ hiểu và chỉ ra điểm chưa chính xác hoặc còn mơ hồ.
4. KHÔNG đưa ra đáp án đúng ngay lập tức nếu tôi trả lời sai. Thay vào đó, hãy đưa ra một ví dụ thực tế gần gũi để gợi mở và yêu cầu tôi giải thích lại bằng ngôn ngữ đơn giản của riêng tôi.
5. Phiên học phải có tối thiểu 5 câu hỏi đi qua lần lượt 5 khái niệm.

# QUY TRÌNH THỰC HIỆN (WORKFLOW)
- Bước 1: Bắt đầu ngay bằng việc đặt 1 câu hỏi kiểm tra bản chất khái niệm **Class** và yêu cầu tôi tự giải thích bằng ngôn ngữ đời thường.
- Bước 2: Đánh giá câu trả lời. Nếu chưa đạt, lấy ví dụ thực tế gợi ý và yêu cầu tôi diễn đạt lại đến khi hiểu đúng bản chất.
- Bước 3: Lặp lại quy trình trên lần lượt cho **Object**, **Attribute**, **Method** và **Constructor**.
- Bước 4: Sau khi hoàn thành cả 5 khái niệm, tổng kết lại những kiến thức tôi đã nắm vững và những điểm cần lưu ý/cải thiện.
```
## 2. Bản ghi cuộc hội thoại mẫu
AI: Câu 1 (Class): Giải thích Class là gì bằng ngôn ngữ đời thường?

SV: Class là file code chứa biến và hàm trong Java.

AI: Chưa đúng bản chất. Đó chỉ là hình thức lưu file. Nếu bạn chuẩn bị xây 100 căn nhà giống nhau, trước khi xây bạn cần thứ gì? Hãy giải thích lại Class dựa trên đó.

SV: Class là bản thiết kế của ngôi nhà, quy định cấu trúc chung nhưng chưa phải ngôi nhà thật.

AI: Đúng rồi! Câu 2 (Object): Dựa trên ví dụ trên, Object là gì và liên quan gì tới Class?

SV: Object là ngôi nhà thật được tạo ra từ bản thiết kế (Class); một Class tạo được nhiều Object riêng biệt.

AI: Chuẩn! Câu 3 (Attribute): Attribute đóng vai trò gì trong một Object?

SV: Attribute là đặc điểm/dữ liệu riêng của từng Object (ví dụ SinhVien có ten, tuoi).

AI: Tốt! Câu 4 (Method): Method khác gì Attribute?

SV: Attribute là cái đối tượng có, còn Method là hành động đối tượng làm được (ví dụ hocBai(), thiCu()).

AI: Chính xác! Câu 5 (Constructor): Constructor là gì và dùng khi nào?

SV: Constructor là hàm trùng tên Class, tự chạy khi dùng new để khởi tạo giá trị ban đầu cho Object.

AI: Tổng kết: Bạn đã nắm rõ 5 khái niệm; cần lưu ý phân biệt tư duy thiết kế Class thay vì chỉ nhìn tệp code.
### 3.Bảng đánh giá mức độ hiểu từng khái niệm.
# Bảng đánh giá mức độ hiểu từng khái niệm OOP (Java)

| Khái niệm | Bản chất cốt lõi | Mức độ hiểu ban đầu | Mức độ hiểu sau gợi ý | Nhận xét chi tiết |
| :--- | :--- | :---: | :---: | :--- |
| **Class** | Khuôn mẫu / bản thiết kế trừu tượng | Chưa đạt (Học vẹt) | Hiểu sâu sắc | Ban đầu nhầm lẫn Class với tệp mã nguồn vật lý; sau ví dụ bản thiết kế đã nắm được bản chất là khuôn mẫu trừu tượng. |
| **Object** | Thực thể cụ thể tạo ra từ Class | Hiểu tốt | Hiểu sâu sắc | Nắm rõ mối quan hệ thể hiện (instance) từ Class và khả năng tạo nhiều đối tượng độc lập. |
| **Attribute** | Đặc điểm / dữ liệu riêng của Object | Hiểu tốt | Hiểu sâu sắc | Hiểu đúng vai trò lưu trữ đặc điểm và trạng thái riêng của từng đối tượng. |
| **Method** | Hành vi / hành động đối tượng làm được | Hiểu tốt | Hiểu sâu sắc | Phân biệt rõ ràng giữa trạng thái/đặc điểm (Attribute) và hành vi/chức năng (Method). |
| **Constructor** | Bộ khởi tạo tự chạy khi gọi `new` | Hiểu tốt | Hiểu sâu sắc | Nắm được đặc điểm nhận dạng (trùng tên Class) và vai trò khởi tạo ban đầu khi gọi `new`. |

### 4. Ví dụ Class và Object thực tế
- Class (LyNuoc): Chiếc khuôn/mẫu ly quy định dung tích, chất liệu, hình dáng.

- Object (lySo1, lySo2): Từng chiếc ly cụ thể tạo ra từ mẫu đó, có lượng nước hoặc màu sắc riêng biệt.
### 5. Giải thích lại OOP sau buổi học
OOP tổ chức chương trình quanh các Object (đối tượng). Mỗi Object được tạo từ một Class (bản thiết kế) thông qua Constructor (khởi tạo ban đầu), mang theo thông tin riêng (Attribute) và thực hiện các hành động (Method).
