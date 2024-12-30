+++
title = '6. Quản Lý Ngoại Lệ (Exception Handling) trong Java'
date = 2024-06-23T14:38:33+02:00
draft = false
type = 'blog'
+++

Trong Java, việc quản lý ngoại lệ rất quan trọng để đảm bảo chương trình không bị dừng đột ngột khi gặp lỗi. Các thành phần chính của quản lý ngoại lệ:

try-catch: Chạy mã trong khối try và nếu có ngoại lệ, chuyển sang khối catch để xử lý.
throw: Dùng để ném một ngoại lệ.
throws: Dùng trong khai báo phương thức để thông báo về ngoại lệ mà phương thức có thể ném ra.
Ví dụ về sử dụng try-catch:

try {
    int result = 10 / 0;
} catch (ArithmeticException e) {
    System.out.println("Không thể chia cho 0");
}
