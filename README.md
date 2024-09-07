# Xây dựng game indie Yacht Quest cho nền tảng Steam

## MỞ ĐẦU

## Chương I: Nghiên cứu thị trường Game indie

Game indie là gì? Nghiên cứu thị trường game indie là gì và như thế nào?

Steam là gì?

Trình bày giải thích là mình sẽ chọn thị trường nghiên cứu và dự tính phát hành là steam vì phí phát hành thấp và dễ dàng tiếp cận.

Nghiên cứu các game trên steam, lập bảng so sánh từ số liệu khảo sát: thấy rằng dòng game có độ chênh lệch tỷ lệ người chơi so với số lượng game cùng thể loại lớn nhất là roguelike deck builder. (Lượng người chơi lớn trong khi có ít đối thủ cạnh tranh)

https://www.youtube.com/live/WezMZrk32M4?t=405

Thể loại roguelike deck builder là gì?

-   Nó là thể loại kết hợp deck builder với yếu tố roguelike.
-   Deck builder là game tư duy chiến thuật, có hệ thống nâng cấp trang bị, trang bị thường là thẻ bài (nhưng cũng có thể là súc sắc, vũ khí v.v)
-   Roguelike là những game có độ khó cao vì mỗi lần chơi là game tự tạo ra một bàn chơi mới ngẫu nhiên khác hoàn toàn so với lần chơi trước, và khi bị thất bại người chơi phải bắt đầu lại từ đầu.

Viết về nghiên cứu cụ thể các game thuộc thể loại roguelike deck builder nổi bật:

1. Slay the Spire

-   Game sử dụng thẻ bài như Yugioh để thể hiện hành động của người chơi.
-   Nó có độ khó lớn và chiều sâu chiến thuật vô đáy nhưng cảm giác chơi rất đã.
-   Trò chơi không quá là cân bằng, có ván may mắn thì dễ, ván thì khó. Những điều đấy lại làm trò chơi trở nên lôi cuốn.

2. Dicey dungeons

-   Game sử dụng súc sắc làm thành phần chính.
-   Nội dung câu chuyện và cách chơi đơn giản và dễ tiếp cận.
-   Độ khó của trò chơi đơn giản hơn rất nhiều so những game cùng thể loại.

3. Balatro

-   Game sử dụng bài poker và người chơi phải đạt được một số điểm để vượt qua được ải.
-   Trò chơi rất dễ để học cách chơi dễ tiếp cận, thời gian chơi mỗi ván ngắn, xong vẫn có chiều sâu chiến thuật.
-   Trò chơi không quá là cân bằng, có ván may mắn thì dễ, ván thì khó. Những điều đấy lại làm trò chơi trở nên lôi cuốn.

Lập bảng SWOT

=> Kết luận:

-   Game cần dễ tiếp cận, dễ học nhưng có chiều chiến thuật.
-   Lôi chơi phải có đan xen giữa sự quen thuộc và mới mẻ.
-   Hình ảnh không nhất thiết phải quá đẹp và chi tiết, nhưng nó cần phải đặc trưng và cá tính.

## Chương II: Xây dựng trò chơi

### 2.1 Xây dựng nội dung

### 2.1.1. Ý tưởng

Lấy trò chơi Yacht dice là một trò chơi súc sắc truyền thống làm cảm hứng, vì nó là trò chơi súc sắc phổ biến nên nó có sự quen thuộc với người chơi.

Nó có độ ngẫu nhiên nhỏ hơn cả một bộ bài với nhiều thể vài và nhiều chữ giúp dễ dàng học cách chơi, dễ tiếp cận.

Nhưng nó cũng có tiềm năng mở rộng chiều sâu chiến thuật.

### 2.1.2. Gameplay

Gameplay loop là gì?

Cân bằng game như thế nào? (đi sâu vào lý thuyết trò chơi, cách để cần bằng nhân vật, vật phẩm, lối chơi và chiến thuật trong gameplay)

### 2.1.3. Cốt truyện

Cốt truyện đơn giản: Có một con thuyền phép thuật mà nếu bất cứ ai lên trên đó và chiến thắng được một giải đấu Yacht dice tổ chức trên thuyền thì người đấy sẽ được ban một điều ước.

Đây chỉ là một cốt truyện đơn giản để người chơi có động lực để khám phá trò chơi. Sự đơn giản này là để nhằm tôn nên yếu tố quan trọng hơn, đó chính là nhân vật

Khái niệm nhân vật trong game là gì?

Nhân vật là phần quan trọng của em vì nó thể hiện được nhiều cá tính, bắt mắt, cuốn hút, dễ dàng đem ra để làm hình ảnh marketing, dễ dàng xây dựng công đồng ưa chuộng nhân vật… Thậm chí nếu thành công, ta có thể có cơ hội mở rộng và bán các sản phẩm merch như quần áo hoặc phụ kiện mang hình ảnh các nhân vật đó.

Vì vậy nên các nhân vật cần phải đặc trưng và cá tính.

Đi qua một số nhân vật đã thiết kế trong game.

### 2.2. Công nghệ sử dụng

Game engine là gì? Đi sâu vào Godot và vi sao nó lại lý tưởng để làm game indie (vì là phần mềm mã nguồn mở, không bị ràng buộc giấy phép hay thu phí, dễ tiếp cận, đơn giản xong cũng mạnh mẽ và giàu tính năng. Công đồng lớn) Đề cập đến GDscript.

Đề xập qua các mô hình và phương pháp lập trình mà mình sử dụng để làm game

-   Functional Programing
-   Event Driven Programming
-   Entity component system
-   Statecharts

### 2.3. Thiết kế flow người dùng

Vẽ bảng flowchart.

### 2.4. Lập kế hoạch

Lập bảng kế hoạch các bước làm game bao gồm thời gian và chi phí

### 2.5. Phát hành game

Tạo ảnh/video để quảng bá.
Viết nội dung mô tả game để truyền tải, quảng cáo.
Xây dựng page trên nền tảng.
Giới thiệu game cho những người nổi tiếng.

## Chương III: Kết quả

Kết quả đạt được (sản phẩm game Yacht Quest bản demo)

Phân tích đánh giá sản phẩm đạt được

## KẾT LUẬN
