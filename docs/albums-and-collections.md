# Album và Bộ sưu tập

Album là công cụ theo dõi bộ sưu tập dạng bản đồ. Chúng hiển thị bộ sưu tập đã chọn, vị trí hiện tại trong bộ sưu tập, số ảnh đã chụp, các chủ đề còn thiếu và bản xem trước ghép ảnh của những bức ảnh đã lưu cho album đó.

![Cầm một album ảnh ShutterBug](images/album/holding-album.png)

## Lấy album

Theo mặc định, người chơi có thể chế tạo album ảnh bằng cách đặt một tấm kính, giấy và `Sách và túi mực` vào cột giữa của bàn chế tạo. Một số máy chủ cũng cho phép dùng `/sb album` để mở album nhanh chóng.

Cầm album và sử dụng:

- Nhấp chuột trái để chuyển đến bộ sưu tập trước.
- Nhấp chuột phải để chuyển đến bộ sưu tập sau.
- `/sb album refresh` để vẽ lại album trong tay người chơi.

## Đọc tiến trình album

Dòng mô tả album hiển thị trạng thái bộ sưu tập đã chọn:

- **Bộ sưu tập**: số bộ sưu tập hiện tại, chẳng hạn `3/8`.
- **Chủ đề**: tên bộ sưu tập đã chọn.
- **Tiến trình**: số chủ đề đã chụp trên tổng số chủ đề.
- **Ảnh**: danh sách kiểm tra từng chủ đề trong bộ sưu tập đã chọn.

Những chủ đề đã hoàn thành sẽ được đánh dấu để người chơi dễ nhận biết, trong khi các chủ đề chưa chụp sẽ được làm mờ. Mỗi chủ đề cũng có một gợi ý ngắn giúp người chơi biết nên chụp những gì.

![Mô tả và tiến trình album](images/album/album-description.png)

Bản đồ album hiển thị bộ sưu tập bạn chọn dưới dạng một trang ảnh ghép. Những chủ đề chưa được chụp sẽ hiển thị dưới dạng ô trống kèm tên, còn những chủ đề đã hoàn thành sẽ được thay bằng chính bức ảnh đã chụp.

![Album Home Sweet Home hoàn thành một phần](images/album/home-sweet-home-partial.png){ .sb-map }

## Xuất ảnh PNG album

Chạy `/sb album export` để xuất các bộ sưu tập ảnh trong album thành các tệp PNG. ShutterBug sẽ lưu mỗi bộ sưu tập thành một tệp `album.png` trong cùng thư mục với các tệp chủ đề của bộ sưu tập.

```text
plugins/ShutterBug/albums/<player-uuid>/<collection-id>/album.png
```

Dùng `/sb album export <collection>` để xuất riêng một bộ sưu tập, hoặc `/sb album export all` để xuất toàn bộ. Quản trị viên có quyền quản lý album cũng có thể dùng `/sb album export <player> [collection|all]` để xuất album cho người chơi đang trực tuyến.

## Hướng dẫn sử dụng bộ sưu tập tích hợp sẵn

Đây là các bộ sưu tập được ShutterBug cung cấp sẵn. Quản trị viên có thể chỉnh sửa chúng trong `collections.yml`, vì vậy danh sách bộ sưu tập trên máy chủ sau khi tùy chỉnh có thể sẽ khác với mặc định.

### Bưu thiếp

Ghi lại từng khoảnh khắc tuyệt đẹp qua ống kính, để mỗi bức ảnh đều lưu giữ một phần của thế giới quanh bạn. Ước gì bạn cũng ở đây.

![Album Bưu thiếp](images/album/postcards.png){ .sb-map }

| Ảnh | Mô tả | Cách chụp |
| --- | --- | --- |
| **Sunset Plains** | Giờ vàng trên thảo nguyên. | chụp ảnh trong quần xã đồng bằng vào lúc hoàng hôn. |
| **Desert Noon** | Mặt trời rực rỡ trên những đụn cát bất tận. | chụp ảnh trong quần xã sa mạc vào ban ngày. |
| **Jungle Canopy** | Hoang dã nhiệt đới rậm rạp. | chụp ảnh trong quần xã rừng nhiệt đới. |
| **Frozen Peaks** | Cảnh núi non ngoạn mục. | chụp ảnh trong quần xã đỉnh băng giá. |
| **Mushroom Paradise** | Phong cảnh hiếm nhất thế giới. | chụp ảnh trong quần xã đồng nấm. |
| **Cherry Blossoms** | Cánh hoa đào phấp phới trong gió. | chụp ảnh trong quần xã rừng anh đào. |
| **Coral Reef** | Sắc màu rực rỡ dưới nước. | chụp ảnh trong quần xã đại dương san hô. |
| **Lush Cave** | Khu vườn dưới lòng đất. | chụp ảnh trong quần xã hang tươi tốt. |
| **The Deep Dark** | Im lặng. Thứ gì kia. Bóng tối. | chụp ảnh trong quần xã vùng tối sâu. |
| **Crimson Forest** | Khu rừng đỏ kỳ quái của Nether. | chụp ảnh trong quần xã rừng đỏ thẫm tại Địa ngục. |
| **Warped Woods** | Khu rừng xanh lạ lẫm của thế giới ngầm. | chụp ảnh trong quần xã rừng uốn éo tại Địa ngục. |
| **End Islands** | Những hòn đảo tận cùng kỳ lạ. | chụp ảnh trong The End. |

### Phim tài liệu hoang dã

Quan sát thiên nhiên - động vật trong môi trường của chúng.

![Album Phim tài liệu hoang dã](images/album/wildlife-documentary.png){ .sb-map }

| Ảnh | Mô tả | Cách chụp |
| --- | --- | --- |
| **Wolf Pack** | Bầy sói nhỏ. | đưa ít nhất ba con sói vào ảnh. |
| **Bee at Work** | Một chú ong đang thụ phấn. | đưa một con ong vào ảnh. |
| **The Shepherd** | Một con sói và cừu - kẻ săn mồi gặp con mồi. | đưa một con cừu và một con sói vào cùng một ảnh. |
| **Turtle Beach** | Một con rùa trên bờ. | đưa một con rùa vào ảnh khi đang ở quần xã bãi biển. |
| **Axolotl Pool** | Những cư dân hang động dễ thương nhất. | đưa một con axolotl vào ảnh khi đang ở quần xã hang tươi tốt. |
| **Iron Protector** | Golem đứng canh bảo vệ ngôi làng. | đưa một golem sắt và một dân làng vào cùng một ảnh. |
| **Wandering Merchant** | Người buôn hàng và cả hai con thú của ông ta. | đưa một thương nhân lang thang và ít nhất hai con lạc đà thương nhân vào ảnh. |
| **Fox Hunt** | Chú cáo săn cho bữa ăn tiếp theo. | đưa một con cáo và một con gà vào cùng một ảnh. |
| **Strider Crossing** | Đi trên dung nham xuyên Nether. | đưa một con strider vào ảnh khi đang ở Nether. |
| **Parrot Party** | Hai con vẹt trở lên cùng nhau. | đưa ít nhất hai con vẹt vào ảnh. |

### Tạp chí kiến trúc

Chụp mọi công trình chính trong thế giới.

![Album Tạp chí kiến trúc](images/album/architectural-digest.png){ .sb-map }

| Ảnh | Mô tả | Cách chụp |
| --- | --- | --- |
| **Village Square** | Một dân làng trong ngôi làng bình thường. | chụp ảnh một dân làng khi khung hình bao gồm một công trình làng. |
| **Desert Temple** | Kim tự tháp sa thạch. | chụp ảnh khi khung hình bao gồm kim tự tháp sa mạc. |
| **Jungle Temple** | Ẩn trong tán rừng, đầy bẫy. | chụp ảnh khi khung hình bao gồm kim tự tháp rừng. |
| **Ocean Monument** | Pháo đài dưới biển. | chụp ảnh khi khung hình bao gồm Đài tưởng niệm dưới đáy đại dương. |
| **Woodland Mansion** | Hiếm có, cô độc và nguy hiểm. | chụp ảnh khi khung hình bao gồm biệt thự rừng. |
| **Pillager Outpost** | Chúng sẽ bắn khi bạn đang canh khung hình. | chụp ảnh khi khung hình bao gồm tiền đồn cướp bóc. |
| **Nether Fortress** | Nơi quỷ lửa canh giữ các sảnh. | chụp ảnh khi khung hình bao gồm pháo đài Nether. |
| **Bastion Remnant** | Piglins không thích khách du lịch. | chụp ảnh khi khung hình bao gồm di tích Bastion. |
| **Stronghold** | Sâu dưới lòng đất, con đường đến The End. | chụp ảnh khi khung hình bao gồm pháo đài ngầm tới The End, nằm dưới đất. |
| **Ancient City** | Đi cẩn thận, đi nhẹ nhàng... có thứ đang lắng nghe. | chụp ảnh khi khung hình bao gồm thành cổ nơi Warden sinh sống. |
| **End City** | Người chơi đã đánh bại tất cả, để đến được nơi này. | chụp ảnh khi khung hình bao gồm End City. |
| **Shipwreck** | Một con tàu bị đại dương nuốt chửng. | chụp ảnh khi khung hình bao gồm xác tàu đắm. |

### Tình huống hiểm hóc

Mỗi khung cảnh đều ẩn chứa một câu chuyện riêng.

![Album Tình huống hiểm hóc](images/album/danger-close.png){ .sb-map }

| Ảnh | Mô tả | Cách chụp |
| --- | --- | --- |
| **Ticking Time Bomb** | Chụp ảnh TNT đã kích nổ - rồi chạy. | đưa TNT đã kích nổ vào ảnh. |
| **Charged Creeper** | Một creeper bị sét đánh. Cực kỳ dữ. | đưa một con Creeper tích điện vào ảnh. |
| **Warden's Gaze** | Nó biết bạn đang ở đó. Và nó đang nổi giận. | chụp một Warden đang trong trạng thái giận dữ. |
| **Wither Awakens** | Ghi lại khoảnh khắc tạo ra - và hủy diệt. | chụp Wither trước khi xuất hiện. |
| **Death From Above** | Một cái đe rơi - thời điểm là tất cả. | đưa một cái đe đang rơi vào ảnh. |
| **Raid Captain** | Kẻ dẫn đầu đội tuần tra với biểu ngữ đáng ngại. | đưa một con chỉ huy đột kích dẫn đầu đội huỷ diệt dân làng vào ảnh. |

### Những cuộc gặp hiếm có

Những điều mà phần lớn người chơi chỉ từng nghe kể, nhưng chưa một lần tận mắt chứng kiến.

![Album Cuộc gặp hiếm](images/album/rare-encounters.png){ .sb-map }

| Ảnh | Mô tả | Cách chụp |
| --- | --- | --- |
| **Spider Jockey** | Một bộ xương cưỡi nhện - tỷ lệ xuất hiện <1%. | đưa một bộ xương cưỡi nhện vào ảnh. |
| **Chicken Jockey!!** | Cưỡi gà!!!! | đưa một con zombie cưỡi gà vào ảnh. |
| **Pink Sheep** | Cứ 512 con cừu tự nhiên thì có 1 con màu hồng. | đưa một con cừu hồng vào ảnh. |
| **Brown Mooshroom** | Mooshroom bị sét đánh - vô cùng hiếm. | đưa một mooshroom nâu vào ảnh. |
| **Skeleton Horsemen** | Con ngựa xương kỳ quái, triệu hồi bởi sét. | đưa một bộ xương cưỡi ngựa xương vào ảnh. |
| **Baby Zombie in Gold** | Một sinh vật nhỏ bé nhưng đáng sợ, khoác trên mình bộ giáp vàng đầy đủ. | chụp một zombie con đang mặc đầy đủ giáp vàng trong ảnh. |
| **Invisible Mob** | Đi đâu rồi? Ồ, đây rồi. | đưa một quái vật vô hình vào ảnh. |
| **Cows and Cows** | Mooshroom, Mooshroom nâu, Bò lớn và Bò con. | đưa toàn bộ biến thể bò vào một khung ảnh, bao gồm một bò nấm đỏ, một con bò trưởng thành, một con bò nâu và một con bò con. |
| **The Crossing** | Cáo, gà, hạt giống và thuyền – một câu đố kinh điển. | Chụp một con cáo và một con gà chuẩn bị qua sông trong cùng khung hình, với hạt giống lúa trồng ở gần đó. |
| **Herobrine** | Hắn ta có thật. | chụp ảnh một đền thờ Herobrine (lên Youtube tra nhé, dễ làm này). |

### Tự sướng cực độ

Tất cả đều được thực hiện bằng chế độ tự sướng. Lần này, chính bạn mới là nhân vật chính.

![Album Tự sướng cực độ](images/album/extreme-selfies.png){ .sb-map }

| Ảnh | Mô tả | Cách chụp |
| --- | --- | --- |
| **Burning Up** | Tự sướng khi đang bốc cháy. | chụp tự sướng khi người chơi đang bốc cháy. |
| **Last Breath** | Tự sướng với 3 tim trở xuống. | chụp tự sướng khi người chơi đang ở mức máu thấp. |
| **Deep Dive** | Tự sướng khi chìm hoàn toàn. | chụp tự sướng khi đang ở dưới nước. |
| **Free Fall** | Tự sướng khi lao xuống. | chụp tự sướng khi đang rơi trên cao xuống. |
| **Top of the World** | Tự sướng trên mây. | chụp tự sướng trên độ cao Y=200. |
| **Withering Away** | Tự sướng khi chịu hiệu ứng khô héo. | chụp tự sướng khi người chơi đang có hiệu ứng khô héo - Wither. |
| **Into the Darkness** | Tự sướng trong bóng tối hoàn toàn + một cháu Warden đang ở gần. | chụp tự sướng khi người chơi đang có hiệu ứng mù bởi Warden tạo ra. |

### Kết bạn qua ống kính

Chụp ảnh sẽ thú vị hơn khi có bạn bè cùng tham gia.

![Album Kết bạn qua ống kính](images/album/social-butterfly.png){ .sb-map }

| Ảnh | Mô tả | Cách chụp |
| --- | --- | --- |
| **Portrait** | Chụp ảnh một người chơi khác. | đưa ít nhất một người chơi khác vào ảnh. |
| **Duo Selfie** | Tự sướng với một người bạn mới. | chụp tự sướng với ít nhất một người chơi khác trong khung hình. |
| **Squad Goals** | Bốn người chơi trở lên trong một ảnh. | đưa ít nhất bốn người chơi vào một ảnh. |
| **Fashion Show** | Chụp ai đó mặc đầy đủ giáp mạnh nhất (Netherite). | đưa một người chơi mặc đầy đủ giáp Netherite vào ảnh. |
| **Lunch Break** | Chụp một người chơi đang ăn. | đưa một người chơi đang ăn vào ảnh. |

### Ngôi nhà thân yêu

Những tiện nghi giản dị của một ngôi nhà cần có.

![Album Ngôi nhà thân yêu](images/album/home-sweet-home.png){ .sb-map }

| Ảnh | Mô tả | Cách chụp |
| --- | --- | --- |
| **Workbench** | Nơi tất cả bắt đầu. | đưa một bàn chế tạo vào ảnh. |
| **Hot Oven** | Một lò nung đang hoạt động hết công suất. | đưa một lò nung đang cháy vào ảnh. |
| **Treasure Chest** | Một cái rương kho báu đầy tiềm năng. | đưa một cái rương sản sinh tự nhiên hoặc rương bẫy sản sinh tự nhiên vào ảnh. |
| **Good Night** | Đến giờ nghỉ ngơi. | đưa bất kỳ chiếc giường nào vào ảnh. |

### Những quái vật bất tử

Chụp ảnh tất cả các loại quái vật trong trò chơi.

| Ảnh | Mô tả | Cách chụp |
| --- | --- | --- |
| **Zombie** | Quái vật bất tử kinh điển. | đưa một zombie vào ảnh. |
| **Skeleton** | Cung thủ lách cách. | đưa một bộ xương vào ảnh. |
| **Phantom** | Hậu quả của việc thiếu ngủ. | đưa một con phantom chỉ xuất hiện vào ban đêm vô ảnh. |
| **Drowned** | Quái vật bất tử của đại dương. | đưa một con zombie drowned (zombie chết chìm) vào ảnh. |
| **Husk** | Quái vật bất tử của sa mạc. | đưa một con zombie husk vào ảnh. |
| **Stray** | Quái vật bất tử băng giá. | đưa một skeleton stray chỉ xuất hiện vùng băng giá vào ảnh. |
| **Wither Skeleton** | Cao, to, đen hôi. | đưa một con wither skeleton chỉ xuất hiện trong Nether Fortress vào ảnh. |
| **Zombified Piglin** | Ngại va chạm cho đến khi bị khiêu khích. | đưa một zombified piglin vào ảnh. |
| **Zoglin** | Con quái vật bất tử hung hăng. | đưa một zoglin vào ảnh. |

## Ghi chú quản trị

Quản trị viên có thể tạo và chỉnh sửa các bộ sưu tập trong `collections.yml`. Một bộ sưu tập nên có chủ đề rõ ràng, mục tiêu dễ thực hiện và mô tả đủ cụ thể để người chơi hiểu ngay mình cần chụp gì. Sau khi thay đổi, hãy chạy `/sb reload` nếu cần, rồi dùng `/sb album refresh` trong khi đang cầm album để cập nhật nội dung hiển thị.

Các lệnh quản trị hữu ích gồm `/sb album give [player]`, `/sb album status [player] [collection]`, `/sb album reset <player> [collection|all]`, và `/sb album export [player] [collection|all]`.