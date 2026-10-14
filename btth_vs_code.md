# Hướng dẫn Cài đặt và Sử dụng VS Code cho Lớp học

## Phần 1. Báo cáo Phân tích (Input/Output)

Dưới đây là định nghĩa chi tiết về đầu vào (Input) và đầu ra (Output) khi soạn thảo tài liệu bằng Markdown trên StackEdit:

* **Input (Văn bản thô - Plain Text):** 
  - Các tệp mã nguồn lưu trữ ký tự dạng `.md` chứa các ký hiệu cú pháp đặc biệt như dấu huyền ngợt (`` ` ``), thẻ băm (`#`), hoặc gạch đứng (`|`).
  - Ví dụ: `` `python` `` cho inline code, `| Tiêu đề 1 | Tiêu đề 2 |` để định nghĩa bảng, hoặc `* [ ]` để tạo task list.
* **Output (Giao diện render trực quan trên StackEdit):**
  - Trình duyệt xử lý file `.md` thành HTML, hiển thị văn bản với định dạng hoàn chỉnh: các đoạn lệnh được đưa vào khung có màu sắc (Syntax Highlighting), bảng biểu căn chỉnh ngay ngắn, danh sách công việc chuyển thành các ô checkbox tương tác trực tiếp.

---

## Phần 2. Source Code tài liệu hướng dẫn (.md)

### 1. Giới thiệu công cụ
Khi lập trình, việc khai báo biến như `file_name` hoặc `output_path` cần được làm nổi bật bằng Inline Code để phân biệt với văn bản thông thường. 

Nếu bạn muốn gõ ký tự đặc biệt mà không muốn Markdown hiểu lầm là cú pháp định dạng (ví dụ: in đậm hoặc tiêu đề), hãy dùng ký tự Escape `\`. Ví dụ: gõ `\*Lưu ý quan trọng:\*` sẽ hiển thị nguyên văn là \*Lưu ý quan trọng:\*.

### 2. Ví dụ Code Block Python dài có Syntax Highlighting
Dưới đây là đoạn mã Python mẫu dùng để kiểm tra môi trường cài đặt:

```python
def check_environment():
    import sys
    print("Python version:", sys.version)
    print("Môi trường VS Code đã sẵn sàng!")

if __name__ == "__main__":
    check_environment()
```

### 3. Bảng so sánh StackEdit và VS Code
Dưới đây là bảng đánh giá ưu điểm của hai công cụ hỗ trợ viết tài liệu và lập trình:

| Tiêu chí | StackEdit | VS Code |
| :--- | :--- | :--- |
| **Bản chất** | Trình soạn thảo Markdown trực tuyến trên nền web | Môi trường phát triển tích hợp (IDE) đa nền tảng |
| **Ưu điểm chính** | Hỗ trợ xem trước (Live Preview) mượt mà, tiện lợi ghi chú nhanh | Hỗ trợ gỡ lỗi mạnh mẽ, cài đặt hàng nghìn extension lập trình |
| **Đối tượng sử dụng** | Viết tài liệu README, ghi chú cá nhân, chia sẻ nhanh | Phát triển phần mềm chuyên nghiệp, quản lý dự án lớn |

### 4. Task List kiểm tra tiến độ cài đặt lớp học
- [x] Tải và cài đặt thành công Visual Studio Code
- [x] Cài đặt extension Python và GitLens
- [ ] Tạo repository nhóm theo đúng chuẩn `[Tên Lớp]_[Môn Học]_Session08_Ex03`
- [ ] Đẩy commit đầu tiên lên GitHub