# Cấu hình quản trị

![Trích đoạn cấu hình ShutterBug](images/config-excerpt.png)

ShutterBug được cấu hình thông qua các tệp thiết đặt phía máy chủ do plugin tạo ra. Các tệp chính dành cho quản trị viên bao gồm:

| Tệp | Mục đích |
| --- | --- |
| `config.yml` | Hành vi chính của plugin, cài đặt máy ảnh mặc định, thời gian chờ mỗi lần chụp ảnh, chất lượng kết xuất (ảnh chụp), liên kết hướng dẫn, thời gian chụp lại, ngôn ngữ và công thức chế tạo. |
| `collections.yml` | Định nghĩa bộ sưu tập ảnh và tiến trình sưu tầm. |
| `lang/` | Các tệp ngôn ngữ cho thông điệp hiển thị tới người chơi. |

## Quy trình khuyến nghị

1. Cài đặt plugin rồi khởi động máy chủ một lần để các tệp mặc định được tạo.
2. Dừng máy chủ.
3. Cấu hình `config.yml`, `collections.yml` và các thay đổi ở tệp ngôn ngữ.
4. Khởi động máy chủ và kiểm tra bảng điều khiển xem có cảnh báo cấu hình nào không.
5. Dùng `/sb reload` cho các thay đổi trực tiếp được hỗ trợ khi có.
6. Thử nghiệm với nhóm quyền người chơi thông thường, không chỉ bằng tài khoản có quyền OP.

## Các khu vực cấu hình chính

`config.yml` chứa các thiết lập nâng cao của plugin, bao gồm lượng giấy dùng cho mỗi bức ảnh, thời gian chờ giữa các lần chụp, FOV mặc định, âm thanh chụp ảnh, chất lượng ảnh, liên kết đến hướng dẫn, ngôn ngữ và công thức chế tạo máy ảnh.

Các thiết lập quản trị thường được quan tâm gồm:

- Chọn có dùng giấy cho mỗi lần chụp ảnh hay không.
- Thiết lập số giấy cần dùng cho mỗi bức ảnh hoặc mỗi ô bản đồ.
- Điều chỉnh FOV mặc định của máy ảnh và cách ảnh được hiển thị.
- Chọn có hiển thị liên kết đến Wiki công khai trong `/sb help` hay không.
- Bật hoặc tắt công thức chế tạo máy ảnh và lựa chọn nguyên liệu cần thiết.
- Tùy chỉnh ngôn ngữ thông qua thư mục `lang/`.
- Kiểm soát các tính năng nâng cao bằng hệ thống quyền.

![Ví dụ định nghĩa bộ sưu tập ShutterBug](images/collection-definition-example.png)

## Bộ sưu tập

Định nghĩa các bộ sưu tập trong `collections.yml`. Mỗi bộ sưu tập nên có tên dễ hiểu và một chủ đề rõ ràng để người chơi có thể nhận biết ngay. Trước khi đưa bộ sưu tập mới thành thử thách cho người chơi, hãy kiểm tra thực tế bằng cách chụp ảnh trên máy chủ thử nghiệm hoặc cho một nhóm nhân viên nhỏ trải nghiệm trước.

## Tải lại

Dùng `/sb reload` nếu tài khoản của quản trị viên/người chơi có quyền `shutterbug.reload`. Tải lại rất hữu ích sau khi chỉnh sửa tệp cấu hình, ngôn ngữ và bộ sưu tập, nhưng vẫn nên khởi động lại toàn bộ máy chủ sau các thay đổi lớn, đặc biệt là trước sự kiện công khai hoặc ra mắt bộ sưu tập.

![Xác nhận tải lại ShutterBug](images/reload-confirmation.png)

## Sao lưu và kiểm tra

Sao lưu `config.yml`, `collections.yml` và thư mục `lang/` trước mỗi lần cập nhật lớn. Luôn giữ một bản sao của cấu hình đang hoạt động để có thể nhanh chóng khôi phục khi bộ sưu tập hoặc thiết lập mới gặp lỗi.
