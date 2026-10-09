# BÁO CÁO THỰC HÀNH POSTMAN

## 1. Mục tiêu

* Làm quen với công cụ Postman.
* Thực hiện gửi HTTP request.
* Kiểm thử mã trạng thái, dữ liệu JSON và HTTP headers.

## 2. Công cụ

* Postman
* GitHub
* Postman Echo API

## 3. Nội dung thực hành

### 3.1. Kiểm thử GET

* URL: `https://postman-echo.com/get?name=Giang`
* Method: GET
* Kết quả: HTTP 200 OK.
* Kiểm tra: mã trạng thái 200, định dạng JSON và dữ liệu có tên Giang.
* Kết quả kiểm thử: 3/3 test passed.

### 3.2. Kiểm thử mã trạng thái 404

* URL: `https://postman-echo.com/status/404`
* Method: GET
* Mục tiêu: kiểm tra phản hồi HTTP 404.
* Kết quả thực tế: [Bổ sung sau khi sửa script và chạy lại].

### 3.3. Kiểm thử HTTP Header

* URL: `https://postman-echo.com/response-headers?Content-Type=application/json`
* Method: GET
* Mục tiêu: kiểm tra mã trạng thái và header Content-Type.
* Kết quả thực tế: [Bổ sung kết quả Test Results].

## 4. Nhận xét

Postman hỗ trợ gửi HTTP request, quan sát response và viết script để tự động kiểm tra kết quả trả về.

## 5. Kết luận

Qua bài thực hành, em bước đầu nắm được cách sử dụng Postman để kiểm thử API cơ bản.

## 6. Tài liệu tham khảo

* Video hướng dẫn do giảng viên cung cấp.
* https://learning.postman.com/docs/getting-started/quick-start
* https://learning.postman.com/docs/tests-and-scripts/write-scripts/test-scripts/
