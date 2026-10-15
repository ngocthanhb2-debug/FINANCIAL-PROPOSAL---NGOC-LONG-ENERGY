# NL Trả Góp — Ngọc Long Energy

Phiên bản: **2026.10.15.5**

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

## Nhập liệu 4 bước và thẻ Cài đặt (bản 2026.10.15.2)

- Form chia 4 bước, thanh bước dính ở đầu: 1 Khách hàng, 2 Điện và cấu hình, 3 Giá và thanh toán, 4 Kiểm tra và gửi. Dấu ✓ là đủ thông tin, dấu ! là còn thiếu hoặc cần xem lại (chỉ hiện sau khi đã đi qua bước đó). Mục 01 đến 08 vẫn giữ số cũ.
- Bước 4 là thẻ "Kiểm tra trước khi gửi": tóm tắt khách, tiền điện, cấu hình, tiết kiệm, tổng giá trị, hình thức; dòng nào có vấn đề thì bấm Sửa để nhảy về đúng ô.
- Cảnh báo số bất thường (nhắc, không chặn): tiền điện dưới 100.000 đ hoặc trên 100 triệu, tổng giá trị dưới 10 triệu, đơn giá lắp đặt dưới 5 triệu hoặc trên 30 triệu/kWp, inverter bằng 0 hoặc nhỏ hơn một nửa kWp, tiết kiệm lớn hơn 1,3 lần tiền điện, tên khách 1 ký tự. Các cảnh báo này cũng hiện trong hộp nhắc trước khi tải PDF hoặc gửi Zalo.
- Chi phí khác nội bộ (bước 3) và Dự toán sơ bộ (bước 4) nằm trong mục "Nâng cao", mặc định thu gọn.
- Cài đặt chia 4 thẻ: Giá và điện, Quỹ Stride, Gợi ý cấu hình, PDF và chia sẻ. Mỗi nhóm có dòng "Ảnh hưởng" và "Dùng ở"; chấm cam trên thẻ nghĩa là có ô đang khác mặc định. Thẻ đang xem được nhớ khi mở lại.
- Dữ liệu và cách tính không đổi, PDF không đổi.

## Tự đề xuất cấu hình (bản 2026.10.15.3)

- Biến tần chọn theo cỡ chuẩn (3, 4, 5, 6, 8, 10, 12, 15, 20 kW...), nhỏ nhất không nhỏ hơn 85% kWp. Tỷ lệ 85% chỉnh ở Cài đặt, thẻ Gợi ý cấu hình, dùng chung với Bảng gợi ý.
- kWp được chia thêm cho (1 − hao hụt do biến tần nhỏ hơn pin) nên sản lượng thật đủ nuôi điện khách cần.
- Pin lưu trữ làm tròn lên theo 5 kWh (dư dưới 0,5 kWh thì giữ mốc dưới), Bảng gợi ý cũng làm tròn lên.
- Ô mới "Hiệu suất nạp xả pin" (mặc định 95%, cho nhập 80–100%) ở Cài đặt, thẻ Giá và điện.

## Bảng gợi ý cấu hình
Ở đầu mục 02 có thẻ **Bảng gợi ý cấu hình** (cho nhân viên mới chưa quen lên cấu hình thiết bị).
- Chọn **khu vực** (giờ nắng), **kiểu hệ** (hòa lưới hoặc hybrid), **loại điện** (sinh hoạt tính bậc thang EVN, các loại khác tính theo giá bình quân), giá điện và **tỷ lệ điện dùng ban ngày**.
- Chạm mức tiền điện khách muốn tiết kiệm mỗi tháng (từ 1 đến 50 triệu, thêm mức khác nếu cần). Bảng cho **kWp pin, kW biến tần, kWh lưu trữ** (hybrid), **hóa đơn tối thiểu** của khách và **giá trị đầu tư ước tính** theo đơn giá trong Cài đặt.
- Nếu đã nhập tiền điện ở mục 02, dòng nào vượt khả năng của hóa đơn bị làm mờ kèm nhãn "Hóa đơn chưa đủ".
- **Áp dụng vào báo giá** điền các ô công suất, các ô vẫn sửa tay được.
- **Cài đặt, mục 02 · Bảng gợi ý cấu hình**: chỉnh hệ số (tỷ lệ điện dùng được, hybrid tối đa, biến tần/kWp, hệ số pin lưu trữ), thêm xóa từng mức tiết kiệm, điền cứng kWp/kW/kWh cho từng mức. Có Xuất file / Nhập từ file cùng cài đặt khác.
- Số gợi ý để tra nhanh, chưa thay cho khảo sát thực tế (mái, hướng, bóng che).

## Hệ hybrid: tổng giá trị luôn gồm pin lưu trữ
- Tổng giá trị dự án tự tính = kWp × đơn giá lắp đặt (có hệ số loại mái) + kWh lưu trữ × đơn giá hệ lưu trữ. Đổi kWp, kWh hoặc một trong hai đơn giá thì tổng đổi theo.
- Chọn hybrid mà chưa có dung lượng lưu trữ (chưa nhập tiền điện) thì app tự điền tạm khoảng 1 kWh cho mỗi kWp, làm tròn 5 kWh, kèm khung cảnh báo màu cam ở mục 02. Nhập tiền điện rồi bấm Tự đề xuất cấu hình, hoặc dùng Bảng gợi ý cấu hình, hoặc sửa tay ô Lưu trữ thì cảnh báo mất.
- Khi tổng đã gõ tay thì app giữ nguyên số đó. Nếu tổng khác số tự tính theo cấu hình hiện tại, mục 05 hiện khung cảnh báo kèm nút **Tính lại tổng theo cấu hình hiện tại**, và bước kiểm tra trước khi gửi khách cũng nhắc.

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
- **Chia sẻ ứng dụng**: link GitHub chính thức, mã QR, hoặc tải bản sao .html gửi qua Zalo (bản sao mở được không cần mạng, nhưng không tự cập nhật). Link nhập ở **Cài đặt, mục Chia sẻ · Link ứng dụng chính thức**; link mặc định đã cài sẵn là `https://ngocthanhb2-debug.github.io/FINANCIAL-PROPOSAL---NGOC-LONG-ENERGY/`. Link nằm trong file Xuất cài đặt nên nhân viên chỉ cần Nhập từ file.
- **Gửi thông báo bản mới cho nhân viên**: nút trong mục Chia sẻ, soạn sẵn lời nhắn có số phiên bản, nội dung mới và link, chọn Zalo rồi chọn nhóm nhân viên (máy tính thì sao chép rồi dán).
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
Chỉ cần thay `index.html` (Add file → Upload files → Commit). Mỗi bản mới phải tăng số trong dòng `<meta name="nd-version" content="...">` ở đầu `index.html` thì máy người dùng mới hiện thông báo cập nhật. Dòng `<meta name="nd-note" content="...">` ngay bên dưới ghi tóm tắt nội dung mới: nội dung này hiện trên thanh vàng "Có phiên bản mới", trong lời nhắn thông báo và trong thông báo sau khi cập nhật xong. Không cần sửa `sw.js`.

## Phiên bản .4 — Logo mới
- Logo "NGỌC LONG ENERGY" mới đã cập nhật ở màn hình, file PDF và biểu tượng ứng dụng (icon dùng phần biểu tượng tròn của logo).
- Chỉ cần đẩy lại `index.html` lên GitHub (icon nằm sẵn trong file).
- Nếu máy nào đã tự cài logo riêng trong Cài đặt thì logo riêng đó vẫn được ưu tiên.

## Phiên bản .5 — Nút "Lưu Cloud"
- Ở màn hình Xem trước có thêm nút **Lưu Cloud**: gửi cùng lúc file PDF và file hồ sơ (.json, nhập lại để sửa).
- Điện thoại: bảng chia sẻ -> Zalo -> Cloud của tôi -> Gửi. Máy tính: tải 2 file và mở Zalo web để kéo vào Cloud của tôi.
- Sửa lại: tải file .json từ Zalo, vào Hồ sơ -> Nhập từ file.
