# Online Bread Ordering and Management App
LINK figma https://www.figma.com/design/WjWMPWywrGBNauZiZxlnFB/Low-fidelity-prototype-of-mobile-food-ordering-app--Community-?node-id=0-1&m=dev&t=2WGyFKBe4dPXdcTG-1

# Giới thiệu 

Xem menu & tùy chỉnh: Chọn loại bánh mì, thêm/bớt topping (pate, ớt, rau) theo sở thích.

Đặt hàng & thanh toán: Đặt lịch nhận tại quán (Pick-up) hoặc giao tận nơi, thanh toán linh hoạt (tiền mặt, ví điện tử, QR).

Theo dõi đơn & ưu đãi: Cập nhật trạng thái làm bánh theo thời gian thực, tích điểm và áp mã giảm giá.

Nhóm thực hiện

LÊ PHAN QUANG VINH 080206007771

TRẦN NHẬT THÁI 040206001239

NGUYỄN ĐỨC TRUNG 054206006852

# Chọn đề tài và bối cảnh hình thành ý tưởng

Tên đề tài

Ứng dụng Đặt món và Quản lý Bánh mì trực tuyến

# Lý do chọn đề tài

Trong nhịp sống hiện đại vội vã, bánh mì đã trở thành món ăn nhanh quen thuộc, gắn liền với bữa sáng của đông đảo học sinh, sinh viên và người đi làm. Tuy nhiên, hình thức mua bán truyền thống thường gặp nhiều bất tiện: khách hàng phải xếp hàng dài chờ đợi vào giờ cao điểm, dễ xảy ra nhầm lẫn về yêu cầu món (thêm/bớt topping, nước sốt), còn các cửa hàng nhỏ lẻ lại khó quản lý lượng khách và đơn hàng thủ công.

Bên cạnh đó, mặc dù thị trường giao đồ ăn trực tuyến rất phát triển, các ứng dụng lớn thường đi kèm mức phí chiết khấu cao, không tối ưu cho mô hình kinh doanh ẩm thực đường phố quy mô nhỏ và vừa (SMEs).

Từ thực tế đó, nhóm em nảy ra ý tưởng xây dựng một nền tảng chuyên biệt phục vụ cho việc đặt và mua bánh mì nhanh chóng, giúp kết nối trực tiếp người mua với các hộ kinh doanh.

Nhóm lựa chọn đề tài này với mong muốn số hóa một nét văn hóa ẩm thực quen thuộc, mang lại sự tiện lợi tối đa cho khách hàng (tiết kiệm thời gian chờ đợi, tùy biến món ăn linh hoạt) đồng thời giúp các tiệm bánh tối ưu hóa quy trình vận hành và quản lý đơn hàng hiệu quả hơn.

Đây cũng là một đề tài phù hợp để nhóm vận dụng những kiến thức đã học trong môn học, từ thiết kế giao diện tối ưu trải nghiệm người dùng (UX/UI), xử lý giỏ hàng, đồng bộ dữ liệu thời gian thực cho đến xây dựng các chức năng phân quyền (Khách hàng - Cửa hàng - Shipper).

# Lên Ý Tưởng

## 1.Trải nghiệm người dùng 

Ứng dụng sẽ được chia làm 2 giao diện riêng biệt

* Khách hàng (Customer App): Trực quan, sinh động, thao tác cực nhanh

* Quản lý & Bếp (Management / Merchant App): Đơn giản, rõ ràng, hiển thị đơn hàng dạng thẻ/danh sách trực quan để thao tác làm bánh không bị nhầm lẫn.

## 2.Tính năng chính của Khách Hàng

Bánh mì là món ăn nhanh, đặc biệt đông khách vào buổi sáng. Điểm mấu chốt của app là nhanh – chính xác – đúng ý

* Tùy biến ổ bánh mì

  - Chọn loại vỏ bánh (Giòn, giòn rụm, nguyên cám...).

  - Chọn nhân chính (Pâté, thịt nguội, xíu mại, trứng ốp la, gà xé...).

  - Chọn gia vị & rau (Đồ chua, dưa leo, ngò, sốt bơ, sốt ớt, mức độ cay).

  - Ghi chú đặc biệt (Ví dụ: "Nhiều pate, không hành, vỏ nướng giòn").
 
* Chế độ Hẹn Giờ Lấy

  - Khách đặt từ nhà/trên đường đi làm, chọn khung giờ .

  - Khi đến quán chỉ cần quét mã QR để nhận bánh ngay mà không cần xếp hàng.

* Gói Ăn Sáng Định Kỳ 

  - Khách đặt sẵn nguyên tuần (Thứ 2 đến Thứ 6). Tự động gửi thông báo xác nhận món mỗi tối hôm trước.

* Đặt Nhóm 

  - Một người tạo link gom đơn,  tự chọn vị bánh mì của mình, hệ thống tự chia tiền và các gói sale khi đặt nhóm .

## 3. Tính năng chính của Quản Lý & Bếp 

Hệ thống quản lý giúp quán vận hành trơn tru ngay cả trong giờ cao điểm.

* Màn Hình Bếp (Kitchen Display System - KDS)

  - Đơn hàng nhảy về máy tính bảng tại gian bếp theo thời gian thực.

  - Hiển thị rõ ràng các ghi chú đặc biệt (ví dụ: KHÔNG HÀNH, NHIỀU CAY) bằng màu sắc cảnh báo để thợ làm bánh không bị sót.

* Quản Lý Nguyên Liệu & Tồn Kho Auto-Deduct:

  - Mỗi khi bán 1 ổ bánh mì thịt, hệ thống tự động trừ: 1 vỏ bánh, 30g pate, 50g thịt, 10g dưa góp...

  - Cảnh báo khi nguyên liệu sắp hết.

* Báo Cáo & Phân Tích Doanh Thu:

  - Thống kê món bán chạy nhất theo khung giờ.

  - Dự báo lượng nguyên liệu cần chuẩn bị cho ngày hôm sau dựa trên dữ liệu lịch sử.
 
## 4. Mô hình app Online Bread Ordering and Management

<img width="594" height="569" alt="image" src="https://github.com/user-attachments/assets/633a0c83-16d9-4a47-b46c-a82aa5909e57" />

<img width="563" height="571" alt="image" src="https://github.com/user-attachments/assets/7ad2c559-6cef-46d7-8a3e-6d2b56f38262" />

<img width="559" height="567" alt="image" src="https://github.com/user-attachments/assets/0393c5c9-f9f8-4488-aeab-0456e676bf80" />

<img width="562" height="578" alt="image" src="https://github.com/user-attachments/assets/d11a99f8-070e-4e7a-adb6-5f00fa095bf9" />

## 5. Điểm đặc biệt để App của bạn vượt trội hơn các App giao đồ ăn chung

* Tập trung sâu vào Trải nghiệm Bánh mì: Cho phép tùy biến thành phần chi tiết.

* Tối ưu hóa Pick-up: Giải quyết bài toán xếp hàng chờ đợi mua đồ ăn sáng của dân văn phòng/học sinh.

* Chi phí rẻ hơn cho Chủ quán: Không phải chịu chiết khấu hoa hồng cao (20-30%) như các sàn giao đồ ăn lớn.

# BÁO CÁO PHÂN TÍCH THIẾT KẾ GIAO DIỆN & TÍNH NĂNG ỨNG DỤNG

## 1. Tổng quan về nhận diện thương hiệu và phong cách thiết kế (UI/UX)

* Bảng màu chủ đạo (Color Palette): Sử dụng tông màu đỏ tươi (#FF2D34 hoặc tương đương) làm điểm nhấn kết hợp với sắc đen/xám tối lịch lãm và nền trắng sáng. Phong cách này kích thích vị giác, tạo cảm giác năng động, hiện đại và rất đặc trưng của ngành F&B (Food & Beverage).

* Bố cục (Layout): Thiết kế tối giản (Minimalist), các khối thông tin được phân cấp rõ ràng (Hierarchy) giúp người dùng không bị rối mắt, tập trung tối đa vào hình ảnh món ăn trực quan và nút kêu gọi hành động (CTA).

# 2. Phân tích các màn hình chức năng chính trong ứng dụng
## a. Màn hình Chào mừng & Trang chủ (Splash Screen & Home Screen)
* Màn hình khởi động:

- Trưng bày logo thương hiệu GreatTaste kèm hình ảnh một chiếc bánh mì đặc biệt đầy đặn, sắc nét, tạo ấn tượng thèm ăn ngay từ cái nhìn đầu tiên.

* Màn hình Trang chủ:

-  Banner khuyến mãi: Nổi bật với chương trình "Khuyến mãi mùa tựu trường", hỗ trợ điều hướng dạng chấm tròn (pagination dots) để lướt xem các chương trình ưu đãi khác.

-  Phân mục sản phẩm khoa học: Chia rõ thành hai nhóm chính là Bestsellers (Các món bán chạy: Bánh Mì Đặc Biệt, Bánh Mì Gà Nướng, Bánh Mì Chả Cá) và Recommended (Gợi ý thêm: Bánh Mì Chay Đậu Hũ kèm số sao đánh giá 4.8 và số lượng review).

- Thao tác nhanh: Mỗi thẻ sản phẩm đều có nút tắt dấu cộng (+) giúp thêm nhanh vào giỏ hàng mà không cần bấm vào trang chi tiết, cùng nút Browse Menu cố định dưới cùng để khám phá toàn bộ thực đơn.

## b. Màn hình Chi tiết sản phẩm & Tùy chỉnh (Product Detail & Customization)
-  Hình ảnh & Mô tả: Ảnh chụp cận cảnh (close-up) chất lượng cao làm nổi bật nguyên liệu tươi ngon; phần mô tả ngắn gọn thành phần bên trong (pate, chả, thịt, rau thơm).

-  Thanh trượt tùy chỉnh vị giác (Spicy Slider): Cho phép người dùng kéo điều chỉnh độ cay từ Mild (Ít cay) đến Hot (Cay nhiều) – một điểm cộng lớn cho trải nghiệm cá nhân hóa món ăn.

-  Bộ chọn số lượng (Portion Quantity): Tăng/giảm số lượng trực quan bằng nút + và -.

-  Nút hành động kép: Hiển thị rõ giá tiền (ví dụ: 65,000đ) kết hợp nút bấm ORDER NOW tách biệt, rõ ràng.

## c. Màn hình Thanh toán & Xác nhận đơn hàng (Payment & Success Screen)
Tóm tắt đơn hàng (Order Summary): Hiển thị tổng tiền cần thanh toán chính xác (ví dụ: 45,000đ) và ước tính thời gian giao hàng (Estimated delivery time: 15 - 30mins).

Phương thức thanh toán linh hoạt: Hỗ trợ lựa chọn qua thẻ tín dụng/ghi nợ (Credit Card, Debit Card) với thông tin mã hóa bảo mật cuối thẻ (ví dụ: 5105 **** **** 0505), kèm tùy chọn lưu thẻ cho lần thanh toán sau (Save card details for future payments).

Màn hình Thành công (Success State): Biểu tượng dấu check đỏ lớn đi kèm thông báo "Your payment was successful.", giúp người dùng an tâm rằng giao dịch đã hoàn tất và có nút Go Back để quay về trang chủ.

# 3. Đánh giá ưu điểm của hệ thống
* Tối ưu luồng người dùng (User Flow): Từ lúc mở app đến khi thanh toán thành công chỉ qua vài bước ngắn gọn, giảm thiểu tỷ lệ rớt đơn (drop-off rate).

* Cá nhân hóa cao: Tính năng chọn độ cay trực tiếp trên màn hình chi tiết giải quyết trọn vẹn nỗi đau khi đặt đồ ăn qua mạng (khách hàng không phải ghi chú lủng củng bằng chữ).

* Giao diện đồng bộ: Thiết kế hiện đại, mượt mà, đồng nhất giữa các màn hình, rất phù hợp để phát triển thành một đồ án thực tế hoàn chỉnh môn Lập trình di động hoặc Thiết kế UI/UX.

# Định  hướng phát triển trong tương lai

* Đặt và tùy chọn nhân bánh mì.

* Hẹn giờ và lấy hàng qua mã QR.

* Đặt gói ăn sáng định kỳ và Đặt nhóm văn phòng.

* Màn hình Bếp  hiển thị đơn hàng theo thời gian thực.

* Quản lý nguyên liệu và tự động trừ tồn kho.

* Quản lý menu, giá bán và chương trình ưu đãi.

* Thanh toán trực tuyến.

* Báo cáo doanh thu và phân tích khung giờ cao điểm.

* Đánh giá và phản hồi chất lượng món ăn.

* Gợi ý món ăn thông minh bằng AI.

# Kết Luận 

Qua quá trình tìm hiểu ban đầu, nhóm nhận thấy ứng dụng OBOMA có thể giải quyết một nhu cầu khá thực tế của người dùng là đặt mua món ăn nhanh (takeaway) một cách thuận tiện, tùy chỉnh linh hoạt và tiết kiệm thời gian chờ đợi ở các cửa hàng.   

Điểm mà nhóm muốn hướng tới không chỉ là tạo ra một ứng dụng để "mua bán đồ ăn", mà là xây dựng một nền tảng trong đó người mua có thể dễ dàng tìm kiếm, tùy chỉnh món ăn (độ cay, số lượng) theo sở thích, phía cửa hàng có thể quản lý đơn hàng hiệu quả qua hệ thống số hóa và cả hai bên đều có trải nghiệm giao dịch tối ưu.   

Tuy nhiên, nhóm cũng nhận thấy hệ thống vẫn còn nhiều vấn đề cần nghiên cứu thêm, đặc biệt là xử lý đồng bộ thời gian thực (real-time), tối ưu hóa luồng giao vận (shipper), quản lý kho nguyên liệu, bảo mật thanh toán trực tuyến và khả năng mở rộng quy mô cho các tiệm bánh mì truyền thống.
