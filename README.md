# nthugay.
Bạn là một Chuyên gia Lập trình Giao diện Web (Senior Frontend Developer) kiêm Thiết kế UI/UX xuất sắc, chuyên phong cách Soft Aesthetic / Kawaii / Cute Anime. 

Hãy viết toàn bộ mã nguồn (gồm HTML5 và CSS3 hiện đại, hoặc TailwindCSS viết chung trong một file duy nhất) để tạo một trang web: "TỔNG HỢP PROFILE NHÂN VẬT AL".

YÊU CẦU BẮT BUỘC VỀ NGUYÊN TẮC:
- TUYỆT ĐỐI KHÔNG TỰ TIỆN THÊM các mục ngoài yêu cầu (không thêm footer dài dòng, không thêm form liên hệ, không thêm giỏ hàng, không thêm thanh tìm kiếm phức tạp).
- Chỉ triển khai đúng và đủ các mục được liệt kê bên dưới.
- Mã nguồn phải hiển thị đẹp, chuẩn Responsive (tương thích cả điện thoại và máy tính).

1. PHONG CÁCH THIẾT KẾ & BẢNG MÀU:
- Màu chủ đạo: Xanh pastel xinh xắn, ngọt ngào, dịu mắt (Soft Pastel Baby Blue).
  + Nền trang web (Background): Màu xanh pastel rất nhẹ (Gợi ý mã: #E8F4F8 hoặc #E1F0FA).
  + Màu thẻ/khung (Card background): Màu trắng tinh (#FFFFFF) hoặc trắng sữa mờ nhẹ, bo góc lớn (border-radius: 20px - 28px) kèm viền mỏng màu xanh pastel đậm hơn một chút (#BEE3F8) và đổ bóng mềm (box-shadow siêu nhẹ, mịn màng).
  + Font chữ: Dễ thương, tròn trịa, hiện đại (như 'Quicksand', 'Nunito' hoặc font bo tròn tương tự).
  + Điểm nhấn (Accents): Các icon nhỏ xinh, viền đứt nét hoặc hiệu ứng hover nhẹ nhàng như kẹo bông.

2. CẤU TRÚC TRANG WEB (CHỈ GỒM CÁC PHẦN SAU):

--- PHẦN 1: HEADER (TIÊU ĐỀ TRANG) ---
- Một tiêu đề đơn giản, dễ thương: "Hồ Sơ Nhân Vật AL" (hoặc AL Character Profile).
- Font chữ to, màu xanh đậm pastel (#4A7C9B), có thể có 1-2 icon lấp lánh (sparkles) trang trí nhẹ.

--- PHẦN 2: PROFILE NHÂN VẬT CHÍNH (MAIN CHARACTER SECTION) ---
Một khung profile lớn, nổi bật ở trung tâm, bao gồm chuẩn xác:
- [Hình ảnh nhân vật]: Khung ảnh to, bo góc tròn xinh xắn (hoặc khung oval/hình đám mây), có viền trắng dày và viền xanh pastel bên ngoài. (Dùng ảnh placeholder kích thước 400x500 hoặc 500x500).
- [Tên nhân vật]: Nằm nổi bật cạnh/dưới ảnh, font chữ to rõ, ngọt ngào.
- [Nơi gắn link]: Thiết kế thành các nút bấm (Buttons) hoặc thẻ nhỏ hình viên thuốc (pill badge) xinh xắn:
  + Nút để bấm vào xem thông tin/link mạng xã hội/link bài viết (để sẵn thuộc tính href="#" để tôi tự thay link).
  + Hiệu ứng khi rê chuột (hover): Nút nhích nhẹ lên, đổi màu nền xanh pastel đậm hơn.

--- PHẦN 3: CÁC NHÂN VẬT KHÁC (OTHER CHARACTERS SECTION) ---
- Tiêu đề mục: "Các nhân vật khác" (Other Characters).
- Dạng hiển thị: Dạng lưới (Grid) hoặc thanh cuộn ngang (Horizontal Scroll) gồm 4-6 ô nhân vật phụ nhỏ hơn.
- Mỗi ô nhân vật phụ bao gồm:
  + Avatar/Ảnh nhân vật (thu nhỏ, bo tròn dễ thương).
  + Tên nhân vật phụ.
  + Thẻ/Nút bấm gắn link chuyển hướng riêng cho nhân vật đó.

--- PHẦN 4: INTRODUCE KIỂU NHÂN VẬT (CHARACTER TYPES NOTE) ---
- Tiêu đề mục: "Introduce kiểu nhân vật"
- ĐIỀU KIỆN ĐẶC BIỆT: Mục này KHÔNG dùng bảng (table), KHÔNG dùng bài viết văn bản dài dòng. TOÀN BỘ PHẢI ĐƯỢC THỂ HIỆN BẰNG CÁC BONG BÓNG CHAT (CHAT BUBBLES / SPEECH BUBBLES).
- Thiết kế bong bóng chat:
  + Có đuôi nhọn hướng sang trái hoặc phải giống như khung tin nhắn trò chuyện (Messenger / LINE / Manga bubble).
  + Nền bong bóng: Màu trắng hoặc xanh pastel nhạt, viền mềm mại.
  + Nội dung trong các bong bóng chat là các note ngắn về tính cách/kiểu nhân vật (Ví dụ: "Note: Kiểu nhân vật Tsundere ngoài lạnh trong nóng nè~", "Note: Kiểu nhân vật ngây thơ, lúc nào cũng cười tươi!", "Lưu ý: Nhân vật này mang hệ chiến thuật cao...").
  + Sắp xếp so le nhau (trái - phải) tạo cảm giác như một cuộc trò chuyện hoặc các mẩu giấy ghi chú dễ thương bay bổng.

3. KẾT QUẢ ĐẦU RA:
- Hãy trả về toàn bộ code HTML, CSS (và một chút JS nếu cần cho hiệu ứng mượt mà) trong MỘT FILE DUY NHẤT.
- Chú thích rõ ràng nơi tôi cần thay đổi: Link ảnh (URL ảnh), Tên nhân vật, và Link liên kết (href).
- Code sạch sẽ, dễ đọc, không thừa thãi. Bắt đầu viết code ngay bây giờ.
- PROMPT THIẾT KẾ WEBSITE: AI CHARACTER PROFILE

/HUMAN /EXPERT /WEB DESIGN

Thiết kế một website tổng hợp và lưu trữ PROFILE NHÂN VẬT AI với giao diện xinh yêu, hiện đại, dễ sử dụng, mang phong cách xanh pastel (Baby Blue – Mint Blue – Sky Blue).

1. PHONG CÁCH THIẾT KẾ

- Tông màu chủ đạo: xanh pastel, xanh baby, xanh băng và trắng.
- Giao diện đáng yêu, tinh tế, nhẹ nhàng nhưng không quá trẻ con.
- Background xanh pastel có hiệu ứng gradient nhẹ.
- Các khung nội dung bo góc mềm mại, có đổ bóng nhẹ.
- Trang trí bằng các icon ngôi sao, trái tim, mây, hoa nhỏ và sticker.
- Font chữ dễ đọc, thanh lịch.
- Bố cục khoa học, thoáng mắt, dễ thao tác.
- Có hiệu ứng hover và chuyển động nhẹ khi mở các mục.
- Tương thích điện thoại, máy tính bảng và máy tính.

2. TRANG CHỦ – CHARACTER PROFILE

Tạo khu vực quản lý hồ sơ nhân vật với các trường thông tin:

- Nhân vật (phân loại hoặc nhóm nhân vật).
- Tên nhân vật.
- Hình ảnh nhân vật.
- Nơi gắn link (đường dẫn đến nhân vật, website hoặc nền tảng AI).

Yêu cầu:

- Mỗi nhân vật được hiển thị thành một thẻ Profile riêng.
- Hình ảnh nhân vật hiển thị rõ ràng, đẹp mắt.
- Tên nhân vật nằm ngay bên dưới hình ảnh.
- Có vị trí để gắn link và nhấn vào để mở liên kết.
- Có chức năng thêm, chỉnh sửa và xóa hồ sơ.
- Cho phép tải ảnh từ thiết bị hoặc sử dụng đường dẫn ảnh.
- Có thể tìm kiếm nhân vật theo tên.
- Không tự động tạo nội dung mô tả, tính cách, cốt truyện hay thông tin nhân vật.

3. CÁC NHÂN VẬT KHÁC

Tạo một mục riêng có tiêu đề:

「CÁC NHÂN VẬT KHÁC」

- Dùng để lưu trữ những nhân vật chưa được phân loại vào nhóm chính.
- Mỗi nhân vật có hình ảnh, tên và vị trí gắn link.
- Có thể thêm nhiều nhân vật tùy ý.
- Có thể chỉnh sửa, xóa và sắp xếp nhân vật.
- Thiết kế đồng bộ với trang chủ.

4. INTRODUCE KIỂU NHÂN VẬT

Tạo một mục riêng có tên:

「INTRODUCE KIỂU NHÂN VẬT」

ĐÂY LÀ MỤC NOTE, KHÔNG PHẢI MỤC HỒ SƠ.

Yêu cầu giao diện:

- Chỉ sử dụng các bong bóng chat (Chat Bubbles) để ghi chú.
- Các bong bóng chat có màu xanh pastel, xanh trắng và xanh mint.
- Có thể thêm nhiều bong bóng chat tùy ý.
- Mỗi bong bóng cho phép nhập nội dung tự do.
- Có thể chỉnh sửa và xóa nội dung ghi chú.
- Có thể kéo thả và sắp xếp các bong bóng.
- Không tự động tạo danh sách kiểu nhân vật.
- Không tự động thêm ví dụ, mô tả hoặc nội dung ghi chú.
- Để trống hoàn toàn khi người dùng chưa nhập dữ liệu.

5. NGUYÊN TẮC QUẢN LÝ DỮ LIỆU – CỰC KỲ QUAN TRỌNG

- TUYỆT ĐỐI KHÔNG tự thêm nhân vật.
- TUYỆT ĐỐI KHÔNG tự đặt tên nhân vật.
- TUYỆT ĐỐI KHÔNG tự viết profile, tính cách, tiểu sử hoặc cốt truyện.
- Không tự điền dữ liệu mẫu.
- Không tự suy đoán thông tin từ hình ảnh.
- Chỉ hiển thị những thông tin do người dùng cung cấp.
- Giữ nguyên văn nội dung người dùng nhập, không tự ý sửa đổi.
- Cho phép người dùng toàn quyền thêm, sửa, xóa và quản lý dữ liệu.
- Dữ liệu phải được lưu lại khi tải lại trang hoặc đóng trình duyệt.

6. BỐ CỤC WEBSITE

Thanh điều hướng gồm 4 mục:

1. Trang chủ.
2. Nhân vật.
3. Các nhân vật khác.
4. Introduce kiểu nhân vật.

Có thêm:

- Nút + Thêm nhân vật.
- Ô tìm kiếm.
- Khu vực quản lý hình ảnh.
- Nút chỉnh sửa và xóa.
- Giao diện trống đẹp mắt khi chưa có dữ liệu.

7. KẾT QUẢ MONG MUỐN

Một website quản lý Profile nhân vật AI có giao diện xanh pastel xinh yêu, chuyên nghiệp, dễ nhìn và dễ sử dụng.

Ưu tiên thiết kế đẹp, bố cục rõ ràng, thao tác đơn giản và khả năng lưu trữ dữ liệu ổn định.

Lưu ý cuối cùng: WEBSITE CHỈ LÀ CÔNG CỤ LƯU TRỮ VÀ SẮP XẾP THÔNG TIN. KHÔNG PHẢI CÔNG CỤ SÁNG TẠO NHÂN VẬT. KHÔNG ĐƯỢC TỰ Ý THÊM BẤT KỲ NỘI DUNG NÀO.
