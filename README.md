# Bài Tập: Bóc Tách 6 Thành Phần Cốt Lõi Trong Khung Công Thức CREATE

---

## Phần 1: Phân tích lỗi của câu lệnh ban đầu

Câu lệnh gốc của Tuấn: *"Viết bài đăng Facebook về iPhone mới"* mới chỉ chứa thành phần **R (Request - Nhiệm vụ)** ở mức sơ khai, và bỏ sót hoàn toàn 5 thành phần còn lại của khung CREATE.

Hậu quả của việc mắc lỗi **"Ảo tưởng ngữ cảnh"** (nghĩ rằng AI tự động hiểu rõ mọi thứ) và thiếu các thành phần cụ thể được thể hiện qua bảng sau:

| Thành phần CREATE bị bỏ sót | Tác hại cụ thể đối với bài toán của Tuấn |
| --- | --- |
| **1. C - Character (Vai trò)** | AI không biết mình đang đóng vai trò là ai (chuyên gia công nghệ, copywriter chuyên nghiệp hay nhân viên sale), dẫn đến giọng văn chung chung, máy móc và thiếu chiều sâu. |
| **2. E - Examples (Ví dụ mẫu)** | Thiếu định hướng về văn phong thực tế. AI không có mẫu để học cách dùng từ, ngắt đoạn hay cách chèn icon đặc trưng của thương hiệu TechShop. |
| **3. A - Adjustment (Tinh chỉnh / Ràng buộc)** | Không có các giới hạn cụ thể (ví dụ: không được dùng từ sáo rỗng như "công nghệ đỉnh cao", bắt buộc phải nêu rõ giá bán và ưu đãi). Kết quả là bài viết lan man, sáo rỗng. |
| **4. Type of Output (Định dạng đầu ra)** | Không quy định rõ cấu trúc bài đăng (tiêu đề giật gân, thân bài chia bullet point, phần kêu gọi hành động - CTA), khiến AI trả về một khối văn bản lộn xộn, khó nhìn trên Facebook. |
| **5. Extras (Gia vị bổ sung)** | Thiếu thông tin nền tảng quan trọng như: Tên dòng iPhone cụ thể, chương trình khuyến mãi đi kèm, tệp khách hàng mục tiêu (Gen Z/dân văn phòng), dẫn đến nội dung hoàn toàn xa rời thực tế cửa hàng. |

---

## Phần 2: Viết lại Prompt hoàn chỉnh theo Khung CREATE

Dưới đây là câu lệnh đã được tối ưu hóa đầy đủ 6 thành phần để giúp Tuấn thu về một bài đăng Facebook chất lượng cao, đúng nhu cầu thực tế của TechShop:

```text
[C - Character / Vai trò]
Bạn là một Copywriter chuyên nghiệp, am hiểu sâu sắc về công nghệ và phong cách viết nội dung trẻ trung, năng động, bắt trend dành riêng cho khách hàng Gen Z của cửa hàng TechShop.

[R - Request / Nhiệm vụ]
Hãy viết một bài đăng Facebook quảng cáo cho dòng sản phẩm "iPhone 17 Pro Max" vừa mới ra mắt tại cửa hàng, nhằm thu hút khách hàng để lại bình luận nhận tư vấn hoặc ghé cửa hàng trải nghiệm.

[E - Examples / Ví dụ mẫu]
Ví dụ về văn phong mong muốn:
"🔥 [HOT] CHÍNH THỨC MỞ BÁN IPHONE 17 PRO MAX TẠI TECHSHOP! 🔥
✨ Nâng tầm trải nghiệm với Titan hàng không, chip A19 Pro siêu đỉnh và camera zoom quang học cực nét.
💰 Giá mở bán siêu yêu thương chỉ từ X.XXX.000đ, hỗ trợ trả góp 0% cực nhanh gọn!
👉 Ghé ngay TechShop gần nhất hoặc nhắn tin ngay cho shop để chốt đơn sớm nhất nhé!"

[A - Adjustment / Ràng buộc & Tinh chỉnh]
1. Tuyệt đối không sử dụng các từ ngữ sáo rỗng, chung chung như "công nghệ đỉnh cao" hay "sản phẩm tuyệt vời". Thay vào đó, hãy dùng từ ngữ cụ thể, ngắn gọn, thời thượng.
2. Bắt buộc phải làm nổi bật 2 yếu tố: Giá bán khởi điểm (29.990.000đ) và chương trình ưu đãi "Thu cũ đổi mới trợ giá 2 triệu".
3. Giữ độ dài vừa phải, bố cục rõ ràng, trình bày thân thiện với thiết bị di động.

[T - Type of Output / Định dạng đầu ra]
Đầu ra phải tuân theo cấu trúc bài đăng Facebook chuẩn gồm:
- Tiêu đề (Hook) giật gân, có chứa emoji bắt mắt.
- Phần thân bài ngắn gọn làm nổi bật 3 điểm nhấn công nghệ/ưu đãi chính (dùng bullet point).
- Phần kêu gọi hành động (Call to Action - CTA) mạnh mẽ kèm hashtag (#TechShop #iPhone17ProMax).

[E - Extras / Gia vị bổ sung]
- Tệp khách hàng mục tiêu: Học sinh sinh viên, người trẻ mê công nghệ thích cập nhật xu hướng.
- Thông tin cửa hàng: TechShop - 123 Tôn Đức Thắng, Quận 1, TP.HCM. Hotline: 0909.xxx.xxx.

```
