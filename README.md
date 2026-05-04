# Smart-Parking-System

[![GitHub License](https://img.shields.io/github/license/tpc-pascal/Smart-Parking-System)](https://github.com/tpc-pascal/Smart-Parking-System/blob/main/LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/tpc-pascal/Smart-Parking-System)](https://github.com/tpc-pascal/Smart-Parking-System/stargazers)

**Smart Parking System** là một giải pháp quản lý bãi giữ xe thông minh, tích hợp công nghệ nhận diện biển số xe (License Plate Recognition - LPR) để tự động hóa quy trình kiểm soát ra vào, tối ưu hóa không gian đỗ xe và nâng cao tính an ninh.

## 🎉 Tác giả

[![Contributors](https://contributors-img.web.app/image?repo=tpc-pascal/Smart-Parking-System)](https://github.com/tpc-pascal/Smart-Parking-System/graphs/contributors)
<details open>
<summary><b>🔍 Các thành viên</b></summary>

| STT | Tên | MSSV |
|:---:|:---|:---|
| 1 | Nguyễn Thanh Thiên Phước | 2380601773 |
| 2 | Lại Bảo Định | 2380600505 |
| 3 | Trịnh Phú Cường | 2380614500 |
</details>

## 🚀 Tính năng chính

Hệ thống được thiết kế tập trung vào 4 nhóm đối tượng người dùng chính:

* **Cho Chủ xe:** Tự động nhận diện biển số, tra cứu vị trí đỗ và xem lịch sử gửi xe.
* **Cho Người quản lý:** Giám sát luồng xe theo thời gian thực, hiệu chỉnh thông tin biển số và xuất báo cáo doanh thu.
* **Cho Quản trị viên:** Quản lý hạ tầng (Camera, Cổng, Slot đỗ), phân quyền người dùng và cấu hình tham số AI.
* **Tự động hóa:** Tích hợp nhận diện biển số bằng AI (YOLO/OpenCV) với độ trễ thấp và độ chính xác cao.

## 🛠 Công nghệ sử dụng

* **Backend:** ...
* **Database:** PostgreSQL.
* **AI Module:** OpenCV, YOLO, CNN, OCR.
* **Frontend:** ...
* **Documentation:** SRS, ERD, Diagram (Use Case, Sequence, Activity).

## 📁 Cấu trúc thư mục

```
Smart-Parking-System/
├── .github/                                              # Luồng làm việc GitHub Action
│   └── workflows/
│       └── sync.yml
├── data/                                                 # Bộ dữ liệu
│   ├── testing/
│   └── training/
│       └── TRAINING_DATASET.md
├── docs/                                                 # Tài liệu mô tả phần mềm
│   ├── diagrams/
│   │   ├── Activity/
│   │   ├── Relational/
│   │   ├── Sequence/
│   │   └── Use Case/
│   └── srs/
├── hf/                                                   # HuggingFace API
│   ├── function/
│   │   ├── helper.py
│   │   └── utils_rotate.py
│   ├── model/
│   └── yolo/
├── model/                                                # Kết quả mô hình
│   ├── detection/
│   │   ├── LPD_best_weight.pt
│   │   ├── LPD_Train_Colab.ipynb
│   │   └── LPD_yolo.yaml
│   ├── pretrained/
│   │   ├── yolo11m.pt
│   │   ├── yolo11n.pt
│   │   ├── yolo26n.pt
│   │   ├── yolov5l.pt
│   │   ├── yolov5m.pt
│   │   └── yolov5s.pt
│   ├── recognition/
│   │   ├── LPR_best_weight.pt
│   │   ├── LPR_Train_Colab.ipynb
│   │   └── LPR_yolo.yaml
│   └── requirements.txt
├── .gitattributes
├── .gitignore
├── CONTRIBUTING.md
├── CREDITS.md
├── LICENSE
├── README.md
└── TODO.md
```

## 🚅 Bộ dữ liệu

Đọc thêm tại [TRAINING_DATASET.md](./data/training/TRAINING_DATASET.md) và [TESTING_DATASET.md](./data/testing/TESTING_DATASET.md)

## ✈ Hướng dẫn đóng góp

Đọc thêm tại [CONTRIBUTING.md](./CONTRIBUTING.md)

## 🙏 Nguồn tham khảo

Đọc thêm tại [CREDITS.md](./CREDITS.md)
