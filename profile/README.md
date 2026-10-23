<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/commune-dxos/commune-dxos/main/docs/images/logo/logo-ngang-nen-trang.png">
    <img src="https://raw.githubusercontent.com/commune-dxos/commune-dxos/main/docs/images/logo/logo-ngang.png" alt="Logo Commune DX-OS – Chính quyền số Cấp xã" width="420">
  </picture>
</p>

<p align="center">
  <strong>Người dân nộp hồ sơ một lần, cán bộ xã biết hồ sơ đang ở đâu và còn bao lâu tới hạn.</strong><br>
  Hệ điều hành Chính quyền số Cấp xã, mã nguồn mở, chạy trên một máy ở xã.
</p>

<p align="center">
  <a href="https://github.com/commune-dxos/commune-dxos/blob/main/LICENSE"><img src="https://img.shields.io/badge/gi%E1%BA%A5y%20ph%C3%A9p-GPL--3.0--or--later-blue.svg" alt="Giấy phép GPL-3.0-or-later"></a>
  <a href="https://github.com/commune-dxos/commune-dxos/releases/latest"><img src="https://img.shields.io/github/v/release/commune-dxos/commune-dxos?label=phi%C3%AAn%20b%E1%BA%A3n" alt="Phiên bản mới nhất"></a>
  <a href="https://commune-dxos.github.io/commune-dxos/"><img src="https://img.shields.io/badge/trang-t%C3%A0i%20li%E1%BB%87u-0F766E.svg" alt="Trang tài liệu"></a>
</p>

### Bắt đầu từ đâu

| Bạn muốn | Vào đây |
|---|---|
| Xem mã nguồn, cài đặt và chạy thử | [commune-dxos/commune-dxos](https://github.com/commune-dxos/commune-dxos) |
| Đọc hướng dẫn và danh mục thủ tục | [Trang tài liệu](https://commune-dxos.github.io/commune-dxos/) |
| Tải bản phát hành | [Releases](https://github.com/commune-dxos/commune-dxos/releases) |
| Theo dõi lộ trình | [Bảng lộ trình](https://github.com/orgs/commune-dxos/projects/1) · [Mốc theo tuần](https://github.com/commune-dxos/commune-dxos/milestones) |
| Báo lỗi hoặc góp ý | [Tạo issue](https://github.com/commune-dxos/commune-dxos/issues/new/choose) |

### Điểm nổi bật

- **Thêm thủ tục không cần sửa mã.** Mỗi thủ tục là một thư mục `thu-tuc/<ma>/` gồm mô tả, quy trình BPMN và thành phần hồ sơ. Hiện có 2 thủ tục: Đăng ký khai sinh và Chứng thực bản sao từ bản chính.
- **Biết trước cần mang giấy tờ gì.** Thành phần hồ sơ của từng thủ tục khai bằng JSON Schema, công khai để người dân xem trước khi nộp.
- **Không để trễ hạn mới biết.** Hạn giải quyết tự tính theo ngày làm việc, bỏ cuối tuần và ngày lễ; hồ sơ còn từ 1 ngày trở xuống thì hệ thống phát cảnh báo sắp trễ hạn.
- **Hai tầng tách bạch.** Lõi nền tảng chỉ có API (đăng nhập một lần, cổng API, dữ liệu, quy trình); ứng dụng một cửa chỉ gọi lõi qua cổng API.

### Đội phát triển

Đội thi **DTU_DZ_2** · Đại học Duy Tân · OLP Phần mềm Nguồn mở 2026

- [@datnguyen262021](https://github.com/datnguyen262021) (trưởng nhóm)
- [@vuthingockhanh2006dn-arch](https://github.com/vuthingockhanh2006dn-arch)
- [@ky213456](https://github.com/ky213456)

Mã nguồn phát hành theo giấy phép [GPL-3.0-or-later](https://github.com/commune-dxos/commune-dxos/blob/main/LICENSE). Mời đọc [hướng dẫn đóng góp](https://github.com/commune-dxos/commune-dxos/blob/main/CONTRIBUTING.md) và [quy tắc ứng xử](https://github.com/commune-dxos/commune-dxos/blob/main/CODE_OF_CONDUCT.md) trước khi tham gia.
