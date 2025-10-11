# TruckersVN Saveedit tool (công cụ saveedit nhẹ nhất thời điểm hiện tại, chưa tới 4 MB)

## Vui lòng truy cập [trang Releases](https://github.com/lesongvi/truckersvn-saveedit-tool/releases) để tải về phiên bản mới nhất.

## Tính năng Save edit của công cụ vẫn đang trong giai đoạn BETA, hãy đảm bảo cài đặt "Tự động sao lưu" được bật trong cấu hình công cụ, ngoài ra, hãy cứ sao lưu một thư mục hồ sơ mới. Bạn có thể sử dụng chức năng tải lên hồ sơ hoặc file save nếu hồ sơ của bạn quá lớn.

## Tại sao lại là công cụ nhẹ nhất hiện tại?

- TruckersVN Tool hoàn toàn bỏ đi sự cần thiết của việc phải chạy UI bên trên máy tính người dùng. Thay vào đó, người dùng chỉ cần điều khiển công cụ qua web browser. Dưới máy tính chỉ cần cài đặt một chương trình nhỏ gọn (chưa tới 4 MB) để giao tiếp với trình duyệt và xử lý các tác vụ saveedit.

## Cách sử dụng TruckersVN Tool

1. Tải phiên bản mới nhất của TruckersVN Tools.
2. Giải nén, chạy file `truckersvn-tool.exe`. Sẽ có một icon hiển thị ở góc dưới bên phải màn hình của bạn để bạn biết rằng công cụ đang hoạt động.
3. Nhấn chuột phải vào icon HG và chọn "Mở bảng điều khiển" hoặc truy cập trực tiếp qua [https://truckers.vn/tools/tvn-tool/](https://truckers.vn/tools/tvn-tool/).

## Các chức năng hiện tại

> Lưu ý: _danh sách tính năng này có thể không được cập nhật trên README.md thường xuyên, hãy truy cập bảng điều khiển để tự khám phá_

#### Tip: Nếu bạn chỉ cần decrypt SII thay vì sử dụng công cụ trực quan

- Nếu bạn chỉ cần decrypt file SII, bạn có thể qua tab "Save edit", chọn hồ sơ sau đó tiếp tục chọn folder chứa game.sii và info.sii mà bạn muốn decrypt. Công cụ sẽ decrypt nhanh cho bạn. Sau đó bạn có thể bấm nút "Mở thư mục file save đã chọn" để mở nhanh folder chứa file save đó và bắt đầu chỉnh sửa bằng notepad.

### Việc đang làm (có thể release trong phiên bản tiếp theo)


### Cần thử nghiệm (đã release nhưng vẫn trong giai đoạn thử nghiệm)

- Tất cả chức năng liên quan tới save edit
- Đặc biệt là:
  - Import/export rơ moóc
### Việc sẽ lên dự định làm (chưa lên kế hoạch release)

- ATS compatibility (full)
- Đa ngôn ngữ
- Standardize import/export truck/trailer data

### Chức năng đã hoàn thành

#### Remote

- [x] Hỗ trợ Remote (kết nối và sử dụng công cụ trên thiết bị di động, máy tính bảng, các thiết bị khác..)

#### Teleport

- [x] ATS compatibility
- [x] Dịch chuyển nhanh (không cần thoát ra ứng dụng)
- [x] Tự động cấu hình profile sau khi dịch chuyển (độ hao mòn các thành phần, độ hao mòn các thành phần không thể sửa chữa, khối lượng các thành phần, nhiên liệu, biển số, kết nối rơ-moóc,...)
- [x] Có âm thanh phát ra sau khi dịch chuyển (có thể cài đặt)
- [x] Lưu dấu trang vị trí dịch chuyển (có thể dùng để dịch chuyển nhanh sau này)

#### Rơ moóc

- [x] Chỉnh sửa khối lượng rơ moóc
- [x] Chỉnh sửa khối lượng hàng
- [x] Mở khóa rơ moóc ở khu vực hạn chế (rơ moóc HCT, rơ moóc triple, ...)
- [x] Sửa rơ moóc
- [ ] Sửa tất cả rơ moóc
- [x] Đổi rơ moóc nhanh
- [x] Export rơ moóc
- [x] Import rơ moóc
- [x] Sao chép rơ moóc của người chơi khác

#### Xe tải

- [x] Sửa chữa xe tải
- [ ] Sửa chữa tất cả xe tải
- [x] Nạp nhiên liệu
- [ ] Nạp nhiên liệu cho tất cả xe tải
- [x] Thay đổi động cơ và hộp số (UI)
- [ ] Chỉnh sửa số km đã đi
- [x] Đổi xe nhanh
- [x] Export xe tải
- [x] Import xe tải
- [x] Sao chép xe tải của người chơi khác

#### Save edit

- [x] Độ chế xe cực kỳ flexible bằng editor
- [x] Độ chế rơ moóc cực kỳ flexible bằng editor
- [x] Độ chế rơ moóc đôi và nhiều hơn
- [x] Tạo biển số custom
- [x] Chỉnh sửa biển số theo quốc gia
- [x] Lưu biển số để dễ chỉnh sửa sau này
- [x] Lưu dữ liệu biển số
- [x] Tránh conflict tập tin

#### Hồ sơ

- [x] Chỉnh sửa số tiền
- [x] Chỉnh sửa kinh nghiệm
- [x] Mở khóa garage
- [x] Mở khóa thành phố
- [x] Mở khóa đại lý bán xe
- [x] Mở khóa kỹ năng
- [ ] Backup hồ sơ
- [x] Backup hồ sơ (tự động)
- [ ] Clone hồ sơ
- [x] Tải lên tập tin save
- [x] Tải lên hồ sơ
- [ ] Đổi tên hồ sơ
- [ ] Đổi tên công ty
- [x] Chia sẻ GPS

#### Cài đặt

- [x] Đường dẫn đến Documents
- [x] Cài đặt console
- [x] Cài đặt developer mode
- [ ] Dark Mode
- [ ] Đổi ngôn ngữ
- [x] Đổi convoy mode slot lên `128`
- [x] Cài đặt backup (tự động backup sau khi chỉnh sửa file)
- [x] Cài đặt tự động cập nhật lên phiên bản mới

#### Khác
- [x] Anti AFK + spam tin nhắn
- [x] Cập nhật tự động

#### Tính năng hữu ích có thể sẽ thêm trong tương lai

- Chia sẻ trailer và xe tải bằng link
- Tài khoản
- Khám phá toàn bộ đường đi trên bản đồ
- Quản lý màu xe tải

<!--<img alt="image" src="https://github.com/user-attachments/assets/10049bb6-5980-4936-967d-fd1c1d1ccd20" width="30%" />

<img alt="image" src="https://github.com/user-attachments/assets/d03da7b9-f803-4407-920e-e079685f77a8" width="30%" />

<img alt="image" src="https://github.com/user-attachments/assets/118c8910-8a60-48ac-9208-67daaf01e781" width="30%" />-->

## Tổng hợp các lỗi thường gặp
### Tôi không thể sử dụng công cụ được
- Đảm bảo bạn truy cập được các tên miền sau, đây là các tên miền cần thiết để công cụ hoạt động:
  - https://api.lsv.vn (Version, patcher)
  - https://truckers.vn (UI)
  - https://dl.gtavietnam.com - https://www.worldoftrucks.com/ (SCS Utils)
  - https://dl.truckers.vn
  - Vui lòng đảm bảo cổng 18000 của bạn đang trống

## Ghi chú

- Vì đây là dự án cá nhân nhỏ nên tôi chỉ làm khi nào rảnh, vào cuối tuần gì đó. Nếu bạn phát hiện bug hãy liên hệ với tôi qua email ở phần [Author](#author), tôi sẽ trả lời nhanh nhất có thể. Ở những kênh liên lạc khác có thể sẽ có chậm trễ. Cảm ơn.

## Author

- Lê Song Vĩ, <vi@lsv.vn>
