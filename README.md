Đề bài / Yêu cầu

Thiết kế prompt so sánh tính năng iPhone và Samsung

1. Mục tiêu bài tập

Bài tập này giúp các bạn sinh viên rèn luyện tư duy 'Phân tích trước - Ra lệnh sau'. Các bạn sẽ biết cách áp dụng khung CREATE để thiết kế prompt lấy dữ liệu thông số kỹ thuật chuẩn xác, không để AI bịa đặt.

2. Bối cảnh nghiệp vụ thực tế

Khách hàng cần một bài viết so sánh ngắn gọn, chính xác 100% về dung lượng pin và camera giữa iPhone 16 Pro Max và Samsung Galaxy S24 Ultra.

3. Yêu cầu nghiệp vụ chi tiết

1. Hiển thị thông số dạng bảng ngang rõ ràng.

2. Trích xuất chính xác từ trang chủ Apple và Samsung.

3. Nêu bật 2 điểm mạnh lớn nhất của từng dòng máy.

4. Ràng buộc & bẫy dữ liệu lường trước

AI thường tự đoán bừa dung lượng pin thực tế nếu không có dữ liệu cập nhật, hoặc nhầm lẫn giữa phiên bản tiêu chuẩn và phiên bản Pro. Phải bắt AI ghi chữ 'Chưa xác thực' nếu không tìm thấy nguồn chính thống.

5. Yêu cầu đầu ra chi tiết

Bước 1: Phân tích Input và Output:

Xác định rõ những dữ liệu nào cần đưa vào làm đầu vào (Input) và cấu trúc bảng đầu ra mong muốn (Output).

1. Đầu vào (Input)

Đối tượng: Đúng tên iPhone 16 Pro Max và Samsung Galaxy S24 Ultra (tránh nhầm bản thường/Pro).

Thông số cần lấy: Chỉ lấy mục Pin (mAh, giờ phát video, sạc) và Camera (ống kính sau, zoom, camera trước, quay video).

Nguồn dữ liệu: Chỉ trích xuất từ trang chủ Apple (apple.com) và Samsung (samsung.com).

Từ khóa xử lý lỗi: Bắt buộc dùng cụm từ "Chưa xác thực" nếu hãng không công bố thông số.

Tiêu chí	iPhone 16 Pro Max	Samsung Galaxy S24 Ultra

Dung lượng pin (mAh)	(Số liệu hãng / "Chưa xác thực")	(Số liệu hãng / "Chưa xác thực")

Thời lượng phát video	(Số giờ tối đa)	(Số giờ tối đa)

Công nghệ sạc	(Chuẩn sạc / Công suất W)	(Chuẩn sạc / Công suất W)

Camera sau & Zoom	(Độ phân giải từng ống kính + Zoom)	(Độ phân giải từng ống kính + Zoom)

Camera trước	(Độ phân giải MP)	(Độ phân giải MP)

Quay video tối đa	(Độ phân giải + fps)	(Độ phân giải MP)

Bước 2: Viết prompt theo khung CREATE:

Thiết lập prompt đầy đủ các phần: Context (Ngữ cảnh), Request (Nhiệm vụ), Explanation (Giải thích), Action (Hành động), Tone (Giọng điệu), Extras (Ràng buộc).

[Context - Ngữ cảnh]

Tôi cần viết bài tư vấn công nghệ ngắn gọn, chính xác 100% về pin và camera của iPhone 16 Pro Max và Samsung Galaxy S24 Ultra cho khách hàng.

[Request - Nhiệm vụ]
Lập bảng so sánh ngang thông số Pin và Camera của hai máy trên, sau đó nêu 2 điểm mạnh lớn nhất của mỗi dòng máy.

[Explanation - Giải thích]
Bài viết cần độ chính xác tuyệt đối để tư vấn khách hàng, tránh tình trạng AI tự đoán dung lượng pin mAh của iPhone hoặc lấy nhầm thông số của bản tiêu chuẩn.

[Action - Hành động]
1. Chỉ lấy dữ liệu từ trang chủ Apple (apple.com) và Samsung (samsung.com) cho đúng bản iPhone 16 Pro Max và Galaxy S24 Ultra.

2. Kẻ bảng ngang 3 cột (Tiêu chí | iPhone 16 Pro Max | Galaxy S24 Ultra) gồm các mục: Dung lượng pin (mAh), Thời lượng phát video, Công nghệ sạc, Camera sau, Camera trước, Quay video tối đa.

3. Viết 2 gạch đầu dòng ngắn nêu 2 điểm mạnh nhất về pin/camera của mỗi máy.

[Tone - Giọng điệu]
Khách quan, chuyên nghiệp, súc tích.

[Extras - Ràng buộc]

- Không suy đoán, không dùng nguồn bên thứ ba.

- Thông số nào hãng không công bố (như pin mAh của iPhone) bắt buộc ghi: "Chưa xác thực".

- Không nhầm lẫn với bản thường hoặc bản Pro/Plus.

Bước 3: Chạy thử và nộp kết quả:

Gửi prompt lên AI và copy bảng kết quả so sánh thu được.

Tiêu chí	iPhone 16 Pro Max	Samsung Galaxy S24 Ultra

Dung lượng pin (mAh)	Chưa xác thực	5.000 mAh

Thời lượng phát video	Tối đa 33 giờ	Tối đa 30 giờ

Công nghệ sạc	Không dây MagSafe 25W; có dây từ 20W	Có dây 45W; không dây nhanh 2.0

Camera sau	Chính 48MP + Siêu rộng 48MP + Tele 12MP (zoom 5x)	Chính 200MP + Siêu rộng 12MP + Tele 50MP (5x) + Tele 10MP (3x)

Camera trước	12MP	12MP

Quay video tối đa	4K Dolby Vision 120 fps	UHD 8K 30 fps

Điểm mạnh nổi bật

iPhone 16 Pro Max

Thời lượng pin dài hơn: Phát video tối đa 33 giờ, nhỉnh hơn đối thủ 3 giờ.

Quay video mượt và góc rộng nét: Hỗ trợ quay 4K 120 fps cùng camera góc siêu rộng 48MP.

Samsung Galaxy S24 Ultra

Camera đa tiêu cự 200MP: Cảm biến chính độ phân giải cực cao kèm 2 ống kính zoom quang (3x và 5x).

Pin minh bạch và sạc nhanh: Công bố rõ dung lượng 5.000 mAh cùng sạc nhanh có dây 45W.
