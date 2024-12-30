+++
title = '7. Hướng Dẫn Sử Dụng Các Mảng và Danh Sách trong Java'
date = 2024-06-21T14:38:33+02:00
draft = false
type = 'blog'
+++

Trong Java, bạn có thể lưu trữ một tập hợp các giá trị cùng loại bằng cách sử dụng mảng (array) hoặc danh sách (ArrayList).

Mảng: Mảng có kích thước cố định và có thể chứa các giá trị cùng kiểu dữ liệu.

int[] numbers = {1, 2, 3, 4, 5};
System.out.println(numbers[0]);  // In ra 1
ArrayList: Đây là một danh sách động, có thể thay đổi kích thước khi cần thiết.

import java.util.ArrayList;
ArrayList<String> list = new ArrayList<>();
list.add("Java");
list.add("Python");
System.out.println(list.get(0));  // In ra Java
Bài viết sẽ giải thích chi tiết cách sử dụng mảng và danh sách, kèm theo ví dụ về thao tác thêm, sửa, xóa phần tử.