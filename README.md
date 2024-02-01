# Java Tutorial

## First code in Java

Khi đã cài jdk thì ta có thể chạy jshell trên console để chạy lệnh java

## How Java work

**Java Code -> Byte Code -> JVM -> OS**

Để chạy chương trình Java ta cần 2 bước:
- Sử dụng javac để biên dịch java_code_file sang byte code
- Chạy file bytecode (java classname)

Khi xây dựng một chương trình java thì có rất nhiều file, câu lệnh và dependence, và để java xác định nơi bắt đầu chạy nó sử dụng hàm **main** có chữ ký là:
- public static void main(String args[])

### JVM
Các JVM sẽ tương tác với OS
- JVM phụ thuộc vào nên tảng (nghĩa là mỗi nền tảng sẽ có một cách triển khai JVM khác nhau)

### JRE
JRE (Java Runtime Environment)
- JRE bao gồm JVM, thư viện chuẩn của *Java*, và các tệp hỗ trợ khác giúp thực thi ứng dụng Java (Các build-in, các tệp hỗ trợ: cấu hình runtime và các tệp cấu hình khác)
- JRE không bao gồm các công cụ phát triển và gỡ lỗi

*Note: Tất cả thứ này đảm bảo Java không cần phải biên dịch lại trên mọi hệ thống sử dụng Java*

### JDK
JDK (Java Development Kit)
- Bao gồm JRE, trình biên dịch javac, trình gỡ lỗi (jdb), và các trình hỗ trợ khác trong quá trình phát triển

*Thiết bị của người dùng chỉ cần JRE để chạy ứng dụng mà không cần đến JDK*

### Các bước chạy Java
- Biên dịch Java Code: javac java_file_name.java
- Lúc này file java code sẽ được biên dịch ra một file mới gọi là byte code
- File byte code 

## Variable in Java

Variable được sử dụng để chứa giá trị (sử dụng tên biến thay cho giá trị)
- 