# Tìm hiểu về Markdown

## Markdown là gì?

**Markdown**  là một ngôn ngữ đánh dấu với cú pháp văn bản thô, được thiết kế để có thể dễ dàng chuyển thành HTML và nhiều định dạng khác sử dụng một công cụ cùng tên. Nó thường được dùng để tạo các tập tin *readme*, viết tin nhắn trên các diễn đàn, và tạo văn bản có định dạng bằng một trình biên tập văn bản thô.

## Lịch sử về Markdown
Năm 2004, cùng với sự giúp đỡ của [Aaron Swartz](https://en.wikipedia.org/wiki/Aaron_Swartz), [John Gruber](https://en.wikipedia.org/wiki/John_Gruber) đã tạo ra ngôn ngữ Markdown với mục tiêu tạo ra một định dạng văn bản thô "dễ viết, dễ đọc, dễ dàng chuyển thành XHTML (hoặc HTML).
## Ngữ pháp cơ bản
### Tiêu đề
Các lớp tiêu đề từ h1 đến h6 viết bằng cách thêm tương ứng từ 1 đến 6 ký tự # trước đầu dòng.
Kẹp ở đầu và cuối một đoạn text cặp ký tự  * để in nghiêng, ** để in đậm, *** để kết hợp cả hai. Chữ gạch ngang sử dụng cặp ký tự ~~
*In nghiêng*
**In đậm**
***Nghiêng đậm***
~~Gạch ngang~~
### Liên kết
Cách dẫn liên kết là: [alttext]và (url)
[John Gruber](https://en.wikipedia.org/wiki/John_Gruber)
Ngoài ra chúng ta có thể thêm "title" vào sau url trong ().
### Hình ảnh
Chèn hình ảnh giống với cú pháp chèn liên kết, thêm ký tự ! trước cú pháp trên.
![https://blog.ghost.org/](https://blog.ghost.org/content/images/2015/03/markdown-guide-1.jpg)
### Định dạng danh sách
Để định dạng một đoạn text thành các gạch đầu dòng, ta dùng ký tự * và một dấu cách ở mỗi ý và dùng thêm 2 dấu cách ở đằng trước nếu muốn lùi vào một level.
* Châu Âu
* Châu Á
 * Việt Nam
     * Hà Nội
     * Hải Phòng
 * Thái Lan
 
Nếu muốn liệt kê bằng số thì thêm số và một dấu chấm.
1. Number one
2. Number two
3. Number three

### Trích dẫn
Cách viết một trích dẫn: sử dụng ký tự > trước đoạn text.
> Markdown là một ngôn ngữ đánh dấu với cú pháp văn bản thô, được thiết kế để có thể dễ dàng chuyển thành HTML và nhiều định dạng khác sử dụng một công cụ cùng tên.

### Mã code
Có 2 loại code có thể viết trong **Markdown**: *inline code* (code trong dòng) và *code block* (đoạn code riêng).
*Inline code* dùng 1 ký tự ` ở đầu và cuối code.

`Code` trong dòng.
*Code block* dùng 3 ký tự phẩy ngược ở đầu và cuối một đoạn code. Khi muốn cú pháp  hiển thị chính xác với ngôn ngữ của đoạn code thì có thể thêm định danh ngôn ngữ ở ngay sau 3 ký tự ` mở đoạn.

```python
import os
os.system('clear')
```
Tham khảo: [https://kipalog.com/markdown](https://kipalog.com/markdown)
