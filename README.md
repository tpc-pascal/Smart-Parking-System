# Smart-Parking-System

[![GitHub License](https://img.shields.io/github/license/tpc-pascal/Smart-Parking-System)](https://github.com/tpc-pascal/Smart-Parking-System/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/tpc-pascal/Smart-Parking-System)](https://github.com/tpc-pascal/Smart-Parking-System/stargazers)

**Smart Parking System** là một giải pháp quản lý bãi giữ xe thông minh, tích hợp công nghệ nhận diện biển số xe (License Plate Recognition - LPR) để tự động hóa quy trình kiểm soát ra vào, tối ưu hóa không gian đỗ xe và nâng cao tính an ninh.

## 🚀 Tính năng chính

Hệ thống được thiết kế tập trung vào 4 nhóm đối tượng người dùng chính:

* **Cho Chủ xe:** Tự động nhận diện biển số, tra cứu vị trí đỗ và xem lịch sử gửi xe.
* **Cho Người quản lý:** Giám sát luồng xe theo thời gian thực, hiệu chỉnh thông tin biển số và xuất báo cáo doanh thu.
* **Cho Quản trị viên:** Quản lý hạ tầng (Camera, Cổng, Slot đỗ), phân quyền người dùng và cấu hình tham số AI.
* **Tự động hóa:** Tích hợp nhận diện biển số bằng AI (YOLO/OpenCV) với độ trễ thấp và độ chính xác cao.

## 🛠 Công nghệ sử dụng

* **Backend:** ...
* **Database:** SQL Server - Thiết kế theo chuẩn ERD tối ưu.
* **AI Module:** License Plate Recognition sử dụng (OpenCV, YOLO, Contours, CNN/OCR).
* **Frontend:** ...
* **Documentation:** SRS, ERD, Diagram (Use Case, Sequence, Activity).

## 📁 Cấu trúc thư mục

```text
Smart-Parking-System/
├── data/
│   └── training/             # Nơi chứa và quản lý Dataset huấn luyện AI
│       └── DATASET.md        # Tài liệu hướng dẫn sử dụng nguồn dữ liệu
├── docs/                     # Toàn bộ tài liệu kỹ thuật của dự án
│   ├── diagrams/             # Hệ thống sơ đồ minh họa
│   │   ├── Activity/         # Luồng thực thi của các chức năng (AD)
│   │   ├── Relational/       # Thiết kế cơ sở dữ liệu (RD)
│   │   ├── Sequence/         # Tương tác giữa các đối tượng trong hệ thống (SD)
│   │   └── Use Case/         # Đặc tả chức năng từ góc nhìn người dùng (UCD)
│   └── srs/                  # Tài liệu đặc tả yêu cầu phần mềm
├── .gitignore                # Loại bỏ các file rác, file nén nặng và môi trường ảo
├── LICENSE                   # Quy định về quyền sử dụng mã nguồn
└── README.md                 # Tài liệu hướng dẫn tổng quan dự án
```

## 🙏 Nguồn tham khảo

Dự án có sử dụng bộ dữ liệu nhận diện biển số xe từ repository của tác giả:
* **winter2897**: [Vienamese Plate Dataset](https://github.com/winter2897/Real-time-Auto-License-Plate-Recognition-with-Jetson-Nano/blob/main/doc/dataset.md) ([Hướng dẫn tải](./data/training/DATASET.md))

## 🤝 Đóng góp

Để đóng góp, bạn vui lòng thực hiện theo các bước sau:

1.  **Fork** dự án này về tài khoản GitHub của bạn.
2.  **Clone** bản fork về máy cá nhân:
    ```bash
    git clone https://github.com/tpc-pascal/Smart-Parking-System.git
    ```
3.  **Tạo một Branch mới** để thực hiện thay đổi:
    ```bash
    git checkout -b feature/TenTinhNangMoi
    ```
4.  **Commit** các thay đổi của bạn kèm thông điệp mô tả rõ ràng:
    ```bash
    git commit -m "Tự miêu tả tính năng"
    ```
5.  **Push** branch đó lên GitHub:
    ```bash
    git push origin feature/TenTinhNangMoi
    ```
6.  Mở một **Pull Request** từ branch của bạn trên GitHub để xem xét và merge, tránh mâu thuẫn trong code gây ra lỗi.

## 🎉 Tri ân

Rất hoan nghênh sự đóng góp của các cá nhân sau đã giúp dự án hoàn thiện hơn! <br>
[![Contributors](https://contributors-img.web.app/image?repo=tpc-pascal/Smart-Parking-System)](https://github.com/tpc-pascal/Smart-Parking-System/graphs/contributors)

## 💡 Một số lưu ý:
* Đảm bảo code tuân thủ phong cách lập trình chung của dự án.
* Nếu phát hiện lỗi (Bug), mở một **Issue** kèm theo mô tả chi tiết và hình ảnh (nếu có).
