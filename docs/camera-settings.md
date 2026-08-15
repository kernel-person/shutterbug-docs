# Cài đặt máy ảnh

<figure class="sb-figure">
  <img src="../images/settings-menu.png" alt="Menu cài đặt máy ảnh ShutterBug">
  <figcaption>Menu cài đặt điều khiển hồ sơ kết xuất, kích thước, FOV, phơi sáng và bộ lọc trước khi chụp ảnh tiếp theo.</figcaption>
</figure>

Bạn có thể dùng `/sb settings` hoặc nhấp chuột phải khi đang cầm máy ảnh để điều chỉnh các thiết lập cho bức ảnh trước khi chụp. Những thiết lập này được lưu riêng cho từng người chơi, nên thay đổi trên máy ảnh của bạn sẽ không ảnh hưởng đến máy ảnh của người khác.

<div class="sb-callout">
  <strong>Giá trị ảnh được lưu trong metadata PNG xuất ra.</strong> Các nhãn so sánh dưới đây sử dụng chế độ, FOV, phơi sáng, bộ lọc, kích thước ảnh, số ô bản đồ và kích thước ảnh do ShutterBug ghi lại.
</div>

## Cách sử dụng menu

| Ô | Cài đặt | Cách thay đổi |
| --- | --- | --- |
| Mode | Hồ sơ kết xuất | Nhấp để chuyển vòng. Các hồ sơ kết xuất (HQ) yêu cầu quyền riêng biệt mới dùng được. |
| Size | Kích thước ảnh | Nhấp để chuyển cỡ ảnh chụp, qua các kích thước bản đồ có sẵn. |
| FOV | Góc nhìn | Nhấp trái để giảm 5, nhấp phải để tăng 5. |
| Exposure | Hệ số phơi sáng | Nhấp trái để giảm 0,25, nhấp phải để tăng 0,25. |
| Filter | Hiệu ứng màu | Nhấp để chuyển vòng qua các bộ lọc có sẵn. |

## Hồ sơ kết xuất

Hồ sơ kết xuất quyết định cách ShutterBug xử lý hình ảnh khi chụp. Hồ sơ thấp ưu tiên tốc độ và cho hình ảnh đơn giản hơn, còn hồ sơ cao tạo hiệu ứng chân thực hơn với ánh sáng, môi trường, mặt nước và các hiệu ứng hậu kỳ.

<figure class="sb-figure">
  <img class="sb-map" src="../images/profile-comparison-contact-sheet.png" alt="So sánh các hồ sơ kết xuất Classic, Normal, Classic HQ, HQ, HQ2, HQ3 và HQ4">
  <figcaption>Tất cả các hồ sơ kết xuất được chụp từ cùng một cảnh đã khóa. Nhãn được lấy từ metadata .PNG.</figcaption>
</figure>

| Chế độ | Phù hợp nhất | Ghi chú |
| --- | --- | --- |
| Classic | Phù hợp để chụp nhanh và xem trước bộ sưu tập. | Hình ảnh sắc nét, đơn giản và gần với giao diện bản đồ gốc. |
| Normal | Phù hợp cho những bức ảnh chụp hằng ngày. | Cân bằng giữa chất lượng hình ảnh và tốc độ chụp. |
| Classic HQ | Phiên bản nâng cao của Classic, cho hình ảnh chất lượng cao hơn. | Yêu cầu quyền HQ/cinematic. |
| HQ | Ảnh trưng bày. | Ánh sáng và bầu không khí tốt hơn. |
| HQ2 | Cảnh có nước, phản chiếu hoặc ánh sáng phong phú hơn. | Yêu cầu quyền HQ/cinematic. |
| HQ3 | Xử lý màu và tông cao cấp. | Yêu cầu quyền HQ/cinematic. |
| HQ4 | Phù hợp cho những bức ảnh dùng để trưng bày. | Chất lượng hình ảnh cao nhất và thời gian kết xuất lâu nhất. |

<figure class="sb-figure">
  <img class="sb-map" src="../images/cinematic-mode-comparison.png" alt="So sánh kết xuất Normal và HQ4">
  <figcaption>Normal là thiết lập mặc định, phù hợp cho nhu cầu chụp ảnh hằng ngày. HQ4 sử dụng kỹ thuật kết xuất 3x3 để cho ra ảnh cuối cùng có chất lượng cao hơn, phù hợp khi chất lượng ảnh quan trọng hơn thời gian kết xuất.</figcaption>
</figure>

## Kích thước ảnh

Kích thước ảnh quyết định số lượng ô bản đồ Minecraft được dùng để tạo thành bức ảnh. Ảnh chỉ dùng một bản đồ sẽ dễ mang theo và phù hợp để hoàn thành các bộ sưu tập. Ảnh có kích thước lớn hơn sẽ hiển thị nhiều chi tiết hơn, thích hợp để treo trên tường, đưa vào phòng trưng bày hoặc dùng làm vật trang trí cho máy chủ.

<figure class="sb-figure">
  <img class="sb-map" src="../images/photo-size-comparison.png" alt="So sánh kích thước ảnh 1x1, 2x2, 3x3 và 5x2">
  <figcaption>Metadata kích thước ảnh hiển thị số bản đồ và kích thước pixel: 1x1, 2x2, 3x3 và 5x2.</figcaption>
</figure>

| Kích thước | Bản đồ | Phù hợp nhất |
| --- | ---: | --- |
| 1x1 | 1 | Ảnh kho đồ, ảnh bộ sưu tập, chia sẻ nhanh. |
| 2x2 | 4 | Trưng bày tường nhỏ với chi tiết rõ ràng hơn. |
| 3x3 | 9 | Trưng bày hình lớn và tài liệu công trình. |
| 5x2 | 10 | Phong cảnh rộng, biểu ngữ và trưng bày toàn cảnh. |

Khi bật tính năng tính phí giấy, số giấy cần dùng sẽ tăng theo kích thước ảnh, tức là số ô bản đồ được sử dụng.

## FOV

FOV là viết tắt của *Field of View* (góc nhìn), quyết định phần thế giới mà máy ảnh có thể thu vào khung hình. FOV thấp cho góc nhìn hẹp và tạo cảm giác đang chụp gần hơn, còn FOV cao cho khung hình rộng hơn và bao quát được nhiều cảnh vật hơn.

<figure class="sb-figure">
  <img class="sb-map" src="../images/fov-comparison.png" alt="So sánh FOV 30, FOV 70 và FOV 125">
  <figcaption>Cùng một khu vực ở FOV 30, FOV 70 và FOV 125, đọc trực tiếp từ metadata PNG của ShutterBug.</figcaption>
</figure>

Dùng FOV thấp cho ảnh chân dung, quái vật hoặc những chi tiết ở xa. FOV ở mức thông thường phù hợp với hầu hết các tình huống chụp ảnh. Với nội thất, công trình lớn, ảnh nhóm và phong cảnh, nên tăng FOV để thu được nhiều cảnh vật hơn. FOV quá cao có thể làm méo các cạnh của khung hình, vì vậy chỉ nên sử dụng khi cần bao quát nhiều không gian hơn thay vì giữ phối cảnh tự nhiên.

## Độ phơi sáng

Độ phơi sáng quyết định độ sáng của bức ảnh sau khi chụp. ShutterBug giới hạn mức phơi sáng trong khoảng từ `0.25x` đến `4.0x`.

<figure class="sb-figure">
  <img class="sb-map" src="../images/exposure-comparison.png" alt="So sánh phơi sáng thấp, bình thường và cao">
  <figcaption>Phơi sáng thấp giữ lại các vùng sáng. Phơi sáng cao hơn giúp bóng tối và cảnh tối dễ đọc hơn.</figcaption>
</figure>

Bắt đầu ở mức gần `1.0x`, sau đó điều chỉnh từng bước nhỏ cho đến khi đạt độ sáng phù hợp. Thông thường, chỉ cần thay đổi một chút là đủ.

## Bộ lọc

Bộ lọc được áp dụng sau khi ảnh hoàn tất quá trình kết xuất, giúp thay đổi màu sắc và tông hình của ảnh. Chúng chỉ tác động lên bức ảnh được chụp, không làm thay đổi thế giới trong trò chơi.

<figure class="sb-figure">
  <img class="sb-map" src="../images/filter-comparison.png" alt="So sánh các bộ lọc None, Sepia, Black and White, Inverted, Warm, Cool và Vintage">
  <figcaption>Mọi bộ lọc được hiển thị trên cùng một cảnh với FOV 70 và phơi sáng 1x.</figcaption>
</figure>

| Bộ lọc | Hiệu ứng | Phù hợp cho |
| --- | --- | --- |
| None | Không áp dụng bộ lọc màu, giữ nguyên màu sắc ban đầu của ảnh. | Phù hợp cho ảnh thông thường và những trường hợp cần giữ màu sắc chính xác. |
| Sepia | Tông màu ấm, mang cảm giác hoài niệm như những bức ảnh cũ. | Phù hợp với công trình cổ, khung cảnh ấm cúng hoặc các bộ sưu tập ảnh. |
| Black & White | Chuyển ảnh sang tông đen trắng, loại bỏ toàn bộ màu sắc. | Phù hợp với ảnh kiến trúc, ảnh có độ tương phản cao và những khung cảnh mang tính nghệ thuật. |
| Inverted | Đảo ngược toàn bộ màu sắc trong ảnh. | Phù hợp với ảnh mang tính thử nghiệm, hiệu ứng nghệ thuật hoặc các sự kiện đặc biệt. |
| Warm | Tăng sắc cam và tạo tông màu ấm cho ảnh. | Phù hợp với ảnh hoàng hôn, làng mạc và không gian nội thất. |
| Cool | Tạo tông màu lạnh với sắc xanh rõ hơn. | Phù hợp với ảnh chụp trong không gian tuyết, ban đêm, đại dương và The End. |
| Vintage | Tạo màu sắc và cảm giác hoài cổ cho ảnh. | Phù hợp với ảnh phong cảnh, ảnh kỷ niệm, ảnh kiểu bưu thiếp và các bộ sưu tập ảnh mang phong cách cổ điển. |

## Kính ngắm

<figure class="sb-figure">
  <img src="../images/viewfinder-overlay.png" alt="Lớp phủ kính ngắm máy ảnh ShutterBug khi ngắm">
  <figcaption>Kính ngắm giúp đóng khung ảnh trước khi tốn giấy chụp hoặc chờ kết xuất.</figcaption>
</figure>

Nhấp chuột trái khi đang cầm máy ảnh để mở kính ngắm. Sử dụng kính ngắm để kiểm tra chủ thể đã nằm gọn trong khung hình chưa, góc nhìn (FOV) có quá hẹp hoặc quá rộng không và khung hình lớn hơn có thể bao quát đầy đủ khung cảnh hay không.

Khi đã căn khung hình ưng ý, nhấn Shift rồi nhấp chuột phải để chụp ảnh. Nhấn Shift rồi nhấp chuột trái để chụp ảnh tự sướng.

## Chi phí giấy chụp

Nếu `consume-paper` được bật, ShutterBug sẽ dùng giấy khi người chơi chụp ảnh trong chế độ sinh tồn. Số giấy cần dùng phụ thuộc vào cấu hình máy chủ và kích thước ảnh.

<figure class="sb-figure">
  <img src="../images/paper-cost-settings.png" alt="Chi phí giấy hiển thị trong trợ giúp hoặc cài đặt">
  <figcaption>Máy chủ có thể hiển thị chi phí giấy hiện tại trong trợ giúp hoặc cài đặt. Ảnh lớn hơn thường tốn nhiều giấy hơn.</figcaption>
</figure>

Hành vi tiêu biểu:

<div class="sb-compact-list" markdown>

- Ảnh một bản đồ tốn ít giấy hơn.
- Ảnh lớn hơn tạo ra nhiều ô bản đồ hơn.
- Người chơi chế độ sáng tạo - Creative hoặc chế độ khán giả - Spectator có thể được miễn.
- `/sb help` có thể hiển thị chi phí giấy hiện tạim khi có áp dụng.

</div>

## Thiết lập mẫu

| Mục tiêu | Cài đặt gợi ý |
| --- | --- |
| Ảnh bộ sưu tập nhanh | Chế độ Normal, kích thước 1x1, FOV 70, phơi sáng 1.0x, không áp dụng bộ lọc. |
| Chân dung người chơi | Chế độ Normal hoặc HQ, FOV thấp, điều chỉnh độ phơi sáng để khuôn mặt được chiếu sáng rõ và cân đối. |
| Công trình lớn | Chế độ Normal hoặc HQ, chọn kích thước ảnh lớn hơn và FOV 80-100 để bao quát toàn bộ công trình. |
| Hang tối | Chế độ Normal hoặc HQ, tăng độ phơi sáng lên 1.25x-2.0x, không dùng bộ lọc hoặc dùng bộ lọc tông ấm. |
| Ảnh trưng bày | Sử dụng chế độ chất lượng cao nhất mà máy chủ hỗ trợ, chọn kích thước ảnh phù hợp để trưng bày và điều chỉnh FOV theo từng khung cảnh. |
