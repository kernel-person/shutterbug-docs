# Quyền

![Các nhóm quyền quản trị ShutterBug](images/permissions-admin-groups.png)

Sử dụng các quyền này với plugin phân quyền của bạn. Giá trị mặc định do plugin định nghĩa.

| Quyền | Mặc định | Mục đích |
| --- | --- | --- |
| `shutterbug.sb` | `true` | Quyền cơ bản để dùng lệnh `/sb`. |
| `shutterbug.use` | `true` | Cho phép sử dụng máy ảnh thông thường, bao gồm chụp ảnh, cài đặt và album khi được bật. |
| `shutterbug.give` | `op` | Cho phép dùng `/sb give` và các công cụ quản trị/kiểm tra dành cho nhân viên được kiểm soát bởi quyền give. |
| `shutterbug.reload` | `op` | Cho phép dùng `/sb reload`. |
| `shutterbug.cinematic` | `op` | Cho phép dùng lệnh hồ sơ kết xuất HQ. |
| `shutterbug.photo.give` | `op` | Cho phép dùng `/sb photo give <player> <image-url>`. |

## Trợ giúp và tự động điền

Danh sách `/sb help` và tính năng tự động điền sẽ chỉ hiển thị những lệnh mà người chơi có quyền sử dụng. Nhờ đó, danh sách lệnh của người chơi luôn gọn gàng, còn quản trị viên có thể giới hạn các lệnh dành cho nhân viên chỉ cho những nhóm được phép sử dụng.

## Nhóm quyền gợi ý

| Nhóm | Quyền gợi ý |
| --- | --- |
| Người chơi | `shutterbug.sb`, `shutterbug.use` |
| Nhiếp ảnh gia | Quyền nhóm Người chơi cộng thêm `shutterbug.cinematic` nếu máy chủ của quản trị viên muốn mở các hồ sơ kết xuất nâng cao cho người chơi đáng tin cậy. |
| Điều hành viên | Có toàn bộ quyền của nhóm Nhiếp ảnh gia và thêm một số quyền được chọn như `shutterbug.give`, dùng khi cần phát máy ảnh hoặc sử dụng các công cụ kiểm tra. |
| Quản trị viên | Tất cả các quyền ShutterBug. |

Hãy kiểm tra kỹ các quyền dành cho nhân sự máy chủ. Lệnh `/sb photo give <player> <image-url>` cho phép đưa ảnh bên ngoài vào bản đồ, vì vậy, chỉ nên cấp quyền này cho những nhân sự đáng tin cậy.

![Nhập ảnh bản đồ từ URL ShutterBug](images/photo-import-url-map.png)
