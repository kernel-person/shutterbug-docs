# Lệnh

![Tự động điền lệnh ShutterBug có phân quyền](images/tab-completion.png)

Dùng `/sb` cho các lệnh ShutterBug. `/shutterbug` là bí danh của cùng một lệnh.

Danh sách lệnh sẽ được hiển thị dựa trên quyền của từng người chơi. `/sb help` chỉ hiển thị những lệnh mà người chơi được phép sử dụng, và tính năng tự động điền cũng chỉ cung cấp các lệnh tương ứng. Nhờ đó, quản trị viên có thể giữ danh sách lệnh của người chơi gọn gàng, đồng thời vẫn cho phép các vai trò được tin cậy sử dụng những công cụ dành cho nhân viên.

## Lệnh người chơi

Các lệnh này dùng cho các thao tác chụp ảnh thông thường. Những lệnh nào được hiển thị còn phụ thuộc vào quyền của người chơi và các tính năng đang được bật trên máy chủ.

| Lệnh | Mục đích |
| --- | --- |
| `/sb` | Hiển thị thẻ khởi động ngắn gọn về chế tạo, chụp ảnh, album, wiki và trợ giúp. |
| `/sb help` | Hiển thị menu trợ giúp ShutterBug được cá nhân hóa. |
| `/sb wiki` | Hiển thị liên kết hướng dẫn công khai do máy chủ cấu hình. |
| `/sb settings` | Mở menu cài đặt máy ảnh. |
| `/sb album` | Nhận hoặc mở bản đồ album cho các bộ sưu tập đã cấu hình. |

Ảnh được chụp trực tiếp bằng vật phẩm máy ảnh, không phải bằng lệnh. Nhấp chuột trái để mở kính ngắm, nhấp chuột phải để mở cài đặt máy ảnh, nhấn Shift rồi nhấp chuột phải để chụp ảnh và nhấn Shift rồi nhấp chuột trái để chụp ảnh tự sướng. Sử dụng `/sb settings` để điều chỉnh góc nhìn, độ phơi sáng, bộ lọc, chất lượng kết xuất và kích thước ảnh trước khi chụp.

## Lệnh quản trị

| Lệnh | Quyền | Mục đích |
| --- | --- | --- |
| `/sb give` | `shutterbug.give` | Đưa máy ảnh thông qua lệnh plugin khi có sẵn. |
| `/sb album give [player]` | `shutterbug.give` | Đưa Album ảnh cho chính bạn hoặc người chơi trực tuyến khác. |
| `/sb album status [player] [collection]` | `shutterbug.give` | Kiểm tra tiến trình album. |
| `/sb album reset <player> [collection\|all]` | `shutterbug.give` | Đặt lại tiến trình album và ảnh thu nhỏ album đã lưu. |
| `/sb reload` | `shutterbug.reload` | Tải lại cấu hình, ngôn ngữ và tệp bộ sưu tập của ShutterBug. |
| `/sb photo give <player> <image-url>` | `shutterbug.photo.give` | Tạo bản đồ ảnh cho người chơi từ URL ảnh. |

## Công cụ quản trị và kiểm tra

Một số phiên bản có thêm các công cụ dành cho quản trị viên và kiểm tra, giúp theo dõi kết quả kết xuất, hiệu ứng hạt, hoạt động của máy ảnh, album và môi trường chụp được kiểm soát. Đây là các công cụ dành cho quản trị viên, không dành cho người chơi thông thường.

Ví dụ có thể xuất hiện cho người gửi có quyền gồm `debug`, `debug_chest`, `design_album`, `testmob`, `testitem`, `testselfie`, `debugtestselfie`, `debugpitchselfie`, `debug_bed`, `locktime`, `lockweather`, `testsound` và `testparticle`.

Vì các công cụ này có phân theo quyền và có thể thay đổi theo bản dựng, quản trị viên nên dựa vào `/sb help` và tính năng tự động điền trong trò chơi để xác nhận danh sách khả dụng chính xác.

## Cần thêm chi tiết?

Chủ máy chủ có thể liên kết người chơi tới `{GITBOOK_URL}` từ văn bản trợ giúp trong trò chơi hoặc hướng dẫn máy chủ.
