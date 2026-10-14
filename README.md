# NL Trả Góp — Ngọc Long Energy

Phiên bản: **2026.10.14.7**

Cùng bộ giao diện với NL Office và NL Hợp Đồng: màu xanh, phông Inter, biểu tượng vẽ sẵn trong file (không cần tải thêm), màn hình chính dạng ô chức năng.

Ứng dụng lập **đề xuất đầu tư điện mặt trời hộ gia đình** theo hai hình thức: **trả góp Quỹ Stride** (6–48 tháng) hoặc **trả thẳng** (lịch thanh toán nhiều đợt). App chỉ là một file HTML, chạy hoàn toàn trên trình duyệt, không có máy chủ.

## Dùng
Mở link GitHub Pages bằng Chrome (Android, máy tính) hoặc Safari (iPhone). Trên điện thoại chọn “Thêm vào màn hình chính”.

Các ô nhập tiền (tiền điện, tổng giá trị, đơn giá, số tiền thanh toán…) tự thêm dấu chấm ngăn cách hàng nghìn ngay khi gõ, ví dụ gõ 3500000 hiện 3.500.000.

## Màn hình chính
- **Báo giá trả góp mới** và **Báo giá trả thẳng mới** mở form trống. Nếu còn số liệu chưa lưu, app hỏi lại một lần.
- **Tiếp tục báo giá**: thẻ trắng hiện khi còn hồ sơ đang nhập dở.
- **Hồ sơ khách**, **Đã gửi khách**, **Cài đặt**, **Hướng dẫn**, **Cài lên màn hình**, **Chia sẻ ứng dụng**.
- Nút **Trang chủ** ở đầu trang (máy tính) và ở thanh tab (điện thoại). Nút **Back** của điện thoại đóng hộp thoại đang mở, bấm tiếp thì về Trang chủ.

## Thanh nút dưới cùng
- Nút lớn: **Xem trước đề xuất PDF** và **Gửi Zalo**.
- Nút nhỏ: **Đơn đề nghị** (chỉ có ở trả góp), **Hồ sơ**, **Khách mới**.

## Gửi khách
- Trước khi tải PDF hoặc gửi Zalo, app nhắc các mục còn thiếu (địa chỉ, tiền điện, kỳ hạn, lịch thanh toán, đang in giá trị hệ thống). App chỉ nhắc, không chặn: bấm **Vẫn gửi** để tiếp tục.
- **Điện thoại**: bấm Gửi Zalo, chọn Zalo trong bảng chia sẻ rồi chọn khách. Lời nhắn được chép sẵn để dán.
- **Máy tính**: app tải PDF về và mở Zalo web, kéo file vào cuộc trò chuyện.
- Nếu mở link từ trong Zalo, bấm ⋯ rồi chọn “Mở bằng trình duyệt” trước.

## Đồng bộ giữa các thẻ trình duyệt
Mở app ở hai thẻ (hoặc hai cửa sổ) cùng một trình duyệt, ví dụ một thẻ xem Trả góp, một thẻ xem Trả thẳng. Ở thẻ thứ hai bấm **Tiếp tục báo giá** (hoặc mở cùng một hồ sơ), số liệu khách nhập ở thẻ này tự cập nhật sang thẻ kia, đầu trang hiện nhãn "⇄ Đồng bộ".
- Mỗi thẻ giữ hình thức đang xem (Trả góp hay Trả thẳng) và tuỳ chọn PDF riêng.
- Đang gõ ở thẻ nào thì thẻ đó không bị ghi đè; thẻ kia cập nhật khi rời ô nhập.
- Khách mới là phiên riêng, không đồng bộ với các thẻ cũ.
- Chỉ đồng bộ trong cùng một trình duyệt trên cùng một máy, không gửi gì ra ngoài. Hai máy khác nhau dùng Xuất file hoặc Nhập từ file.

## Bảng gợi ý cấu hình
Ở đầu mục 02 có thẻ **Bảng gợi ý cấu hình** (cho nhân viên mới chưa quen lên cấu hình thiết bị).
- Chọn **khu vực** (giờ nắng), **kiểu hệ** (hòa lưới hoặc hybrid), **loại điện** (sinh hoạt tính bậc thang EVN, các loại khác tính theo giá bình quân), giá điện và **tỷ lệ điện dùng ban ngày**.
- Chạm mức tiền điện khách muốn tiết kiệm mỗi tháng (từ 1 đến 50 triệu, thêm mức khác nếu cần). Bảng cho **kWp pin, kW biến tần, kWh lưu trữ** (hybrid), **hóa đơn tối thiểu** của khách và **giá trị đầu tư ước tính** theo đơn giá trong Cài đặt.
- Nếu đã nhập tiền điện ở mục 02, dòng nào vượt khả năng của hóa đơn bị làm mờ kèm nhãn "Hóa đơn chưa đủ".
- **Áp dụng vào báo giá** điền các ô công suất, các ô vẫn sửa tay được.
- **Cài đặt, mục 02 · Bảng gợi ý cấu hình**: chỉnh hệ số (tỷ lệ điện dùng được, hybrid tối đa, biến tần/kWp, hệ số pin lưu trữ), thêm xóa từng mức tiết kiệm, điền cứng kWp/kW/kWh cho từng mức. Có Xuất file / Nhập từ file cùng cài đặt khác.
- Số gợi ý để tra nhanh, chưa thay cho khảo sát thực tế (mái, hướng, bóng che).

## Hồ sơ và dữ liệu
- **Tự lưu bản nháp** khi đang nhập. **Hồ sơ khách**: lưu, mở, nhân bản thành phiên bản mới, đổi tên, xuất file, xoá. Hồ sơ không lưu ảnh hoá đơn.
- **Đã gửi khách**: mỗi lần tải PDF hoặc gửi Zalo, app tự lưu một bản kèm số liệu lúc đó. Có các nút Tải lại, Gửi lại Zalo, Dùng lại số liệu, Xuất cho Hợp Đồng, Xoá. Tự xoá sau 1 năm, giữ tối đa 150 file.
- **Xuất cho Hợp Đồng**: tạo file JSON (khách, hệ thống, tài chính) để nhập vào app NL Hợp Đồng.
- **Sao lưu tất cả** (trong Hồ sơ khách) tạo một file .json, gửi vào Zalo “Cloud của tôi”. Đổi máy thì dùng **Nhập từ file**.
- **Cài đặt** (đơn giá, hệ số thi công, hotline, lời nhắn Zalo…) có nút Xuất file / Nhập từ file riêng.
- **Logo, website, email** công ty đặt ở Cài đặt, mục “File PDF · Thông tin công ty và logo”. Lưu trên từng máy.
- Dữ liệu nằm trong trình duyệt của từng máy. Xoá dữ liệu trình duyệt là mất, vì vậy nên sao lưu định kỳ.

## Cài lên màn hình · Chia sẻ · Cập nhật
- **Cài lên màn hình**: ô ở Trang chủ. Android và máy tính hiện hộp cài; iPhone: Safari → Chia sẻ → Thêm vào MH chính.
- **Chia sẻ ứng dụng**: link, mã QR, hoặc tải bản sao .html gửi qua Zalo (bản sao mở được không cần mạng, nhưng không tự cập nhật).
- **Cập nhật**: app tự kiểm tra bản mới khi mở và mỗi giờ (so `nd-version` trong `index.html`). Có bản mới thì hiện thanh vàng “Có phiên bản mới”, bấm **Cập nhật**. Dữ liệu trên máy giữ nguyên. Ở Trang chủ có nút “Kiểm tra cập nhật”.
- **Mất mạng**: `sw.js` lưu sẵn ứng dụng nên vẫn mở, tính toán và xuất PDF được. Đọc hoá đơn bằng ảnh (OCR) cần mạng ở lần dùng đầu.

## Các file
| File | Vai trò |
|---|---|
| `index.html` | Ứng dụng |
| `sw.js` | Chạy offline, lấy bản mới |
| `manifest.webmanifest` | Thông tin cài app |
| `icons/` | Biểu tượng app |
| `.nojekyll` | Báo GitHub Pages phục vụ file nguyên bản |

## Đưa lên GitHub Pages (lần đầu)
1. Tạo repository mới (ví dụ `nl-tra-gop`), chế độ Public.
2. **Add file → Upload files**, kéo thả **toàn bộ nội dung thư mục này** (cả thư mục `icons` và file `.nojekyll`), bấm **Commit changes**.
3. **Settings → Pages**: Deploy from a branch, nhánh `main`, thư mục `/ (root)`, **Save**.
4. Sau 1–2 phút, địa chỉ app là `https://<tên-tài-khoản>.github.io/<tên-repository>/`.

Nếu repository cũ đang dùng bản trước: tải lên đè **tất cả** các file (index.html, sw.js, manifest.webmanifest, icons/). Lần mở đầu sau khi cập nhật, máy người dùng tự chuyển sang bộ nhớ đệm mới.

## Phát hành bản mới
Chỉ cần thay `index.html` (Add file → Upload files → Commit). Mỗi bản mới phải tăng số trong dòng `<meta name="nd-version" content="...">` ở đầu `index.html` thì máy người dùng mới hiện thông báo cập nhật. Không cần sửa `sw.js`.
