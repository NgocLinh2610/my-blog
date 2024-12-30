+++
title = '3. Java Streams và Lambda Expressions: Tối Ưu Hoá Lập Trình'
date = 2024-06-24T14:38:33+02:00
draft = false
type = 'blog'
+++

Java 8 giới thiệu hai tính năng quan trọng là Streams và Lambda Expressions. Chúng giúp làm việc với các bộ sưu tập dữ liệu dễ dàng và hiệu quả hơn.

Lambda Expressions: Cung cấp cách viết mã ngắn gọn hơn cho các phương thức ẩn danh.

List<String> names = Arrays.asList("Alice", "Bob", "Charlie");
names.forEach(name -> System.out.println(name));
Streams: Giúp bạn thực hiện các phép toán như lọc, map, reduce trên các bộ sưu tập một cách dễ dàng.
java
Sao chép mã
List<Integer> numbers = Arrays.asList(1, 2, 3, 4, 5);
numbers.stream().filter(n -> n > 3).forEach(System.out::println);  // In ra 4, 5
