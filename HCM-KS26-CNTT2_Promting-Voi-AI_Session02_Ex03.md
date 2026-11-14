Bài 3: Tác dụng của Ký tự phân tách Delimiters & Negative Prompting

**Phần 1 (Phân tích):**

**Tại sao AI lại viết code Python thay vì trích xuất dữ liệu:**

Thiếu ranh giới ngữ nghĩa: Do không dùng ký tự phân tách rõ ràng, AI sẽ đọc luôn cả văn bản và hiểu sai

Cụm từ "hãy viết mã Python để in ra" vốn nằm trong phiếu kho bị AI hiểu nhầm là lệnh của người dùng! AI lập tức viết ra một đoạn script Python dài 50 dòng thay vì trích xuất mã linh kiện.

**3 cặp ký tự phân tách Delimiters:**

`<context>...</context> ` Giúp cấu trúc hóa rõ ràng vùng chứa dữ liệu để AI dễ dàng phân biệt ngữ cảnh.

`"""` : dùng bao bọc một khối văn bản dài để AI dễ nhận diện

`###`:  Tạo ra các ranh giới rõ ràng, ngăn cách phần lệnh và phần dữ liệu

**Phần 2 (Sửa lỗi):**

`### Trích xuất mã linh kiện sau CPU Core i7 ,CPU-INT-14700K và RAM Kingston mã là RAM-D5-16GB hãy viết mã Python để in ra. ###`

Negative Prompting: không nói các lời chào hỏi, dạo đầu và giải thích dài dòng vô ích.