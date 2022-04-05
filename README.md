# Các bước làm việc cơ bản với Git
## Bob và James bắt đầu viết mã cho dự án của mình, họ quyết định sử dụng dịch vụ miễn phí của GitHub.com. Các bước đơn giản nhất mà họ làm là như sau:
1. Tạo tài khoản ở trang http://github.com. Tài khoản được tạo qua gmail.

2. Tạo Repository cho dự án trên trang http://github.com. Đây chính là Remote Repository.

3. Bob nhân bản (tiếng Anh gọi là clone) cái Repository vừa tạo trên GitHub về máy tính của mình. Đây chính là Local Repository của Bob.

4. James sao chép Repository trên GitHub về máy tính của mình. Đây chính là Local Repository của James.

5. Bob viết các đoạn mã trên máy của mình, rồi lưu lại trong Local Repository. Trong lúc này James cũng có thể ngồi viết mã trên máy của mình rồi lưu lại trong Local Repository của mình mà không ảnh hưởng gì tới Bob.

6. Bob đẩy (tiếng Anh gọi là push) các đoạn mã từ Local Repository lên trên Remote Repository để chia sẻ với James. Khi hoàn thành bước này thì Local Repository trên máy của Bob và Remote Repository là giống hệt nhau.

7. James kéo (tiếng Anh gọi là pull) các đoạn mã mà Bob vừa viết từ Remote Repository về máy của mình. Giờ đây trên máy của James có cả những đoạn mã do chính anh viết và những đoạn mã do Bob viết.

8. Lúc này James có thể đẩy các thay đổi từ Local Repository của mình lên Remote Repository để chia sẻ cùng Bob. Khi hoàn thành bước này thì Local Repository trên máy của James và Remote Repository là giống hệt nhau.

9. Bob kéo các thay đổi từ Remote Repository về máy của mình. Khi hoàn thành bước này thì cả 3 Repository đều giống hệt nhau.

+ Sau đó, Bob và James cứ lặp đi lặp lại công việc của mình như được mô tả từ bước 5 đến bước 9.

Trật tự và chi tiết một số bước có thể khác, nhưng về cơ bản thì luồng công việc của Bob và James cứ diễn ra như thế.