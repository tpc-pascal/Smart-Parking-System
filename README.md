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
│       └── DATASET.md        # Tài liệu hướng dẫn sử dụng dataset
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

## 🎉 Tác giả

[![Contributors](https://contributors-img.web.app/image?repo=tpc-pascal/Smart-Parking-System)](https://github.com/tpc-pascal/Smart-Parking-System/graphs/contributors)
<details open>
<summary><b>🔍 Các thành viên</b></summary>

| STT | Tên | MSSV | Vai trò |
|:---:|:---|:---|:---|
| 1 | Nguyễn Thanh Thiên Phước | 2380601773 | ... |
| 2 | Lại Bảo Định | 2380600505 | ... |
| 3 | Trịnh Phú Cường | 2380614500 | ... |
</details>

## 🙏 Nguồn tham khảo

<details open>
<summary><b>📚 Tài liệu có liên quan</b></summary>

| STT | Tác giả | Liên kết |
|:---:|:---|:---|
| 1 | winter2897 | [Vietnamese Plate Dataset](https://github.com/winter2897/Real-time-Auto-License-Plate-Recognition-with-Jetson-Nano/blob/main/doc/dataset.md) |
</details>
