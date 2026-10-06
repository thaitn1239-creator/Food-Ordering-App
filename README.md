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

## 5. Điểm đặc biệt để App của bạn vượt trội hơn các App giao đồ ăn chung (Grab/Foodpanda)

* Tập trung sâu vào Trải nghiệm Bánh mì: Cho phép tùy biến thành phần chi tiết.

* Tối ưu hóa Pick-up: Giải quyết bài toán xếp hàng chờ đợi mua đồ ăn sáng của dân văn phòng/học sinh.

* Chi phí rẻ hơn cho Chủ quán: Không phải chịu chiết khấu hoa hồng cao (20-30%) như các sàn giao đồ ăn lớn.
