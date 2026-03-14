# 📊 Bộ dữ liệu huấn luyện (Training Dataset)

Thư mục này chứa các tệp tin hướng dẫn và dữ liệu mẫu (Sample) nhằm giúp bạn hình dung cấu trúc dữ liệu trước khi tải bộ dữ liệu đầy đủ.

## 📥 Tải xuống dữ liệu đầy đủ
Do giới hạn dung lượng của GitHub (max 100MB cho Git CLI và 25MB cho Web), dữ liệu thực tế được lưu trữ tập trung tại Google Drive:

* **Link Google Drive:** [License-Plate](https://drive.google.com/drive/folders/14N8wrz-H5rJgPeBCskf4jlIp0dH_Sage?usp=sharing)
* **Tổng dung lượng:** ~452 MB
* **Chi tiết các gói dữ liệu:**
    * `yolo_plate_dataset.zip` (~333.3 MB): Chứa hình ảnh và nhãn (label) phục vụ bài toán **Phát hiện biển số xe** (Detection).
    * `yolo_plate_ocr_dataset.zip` (~118.6 MB): Chứa dữ liệu ký tự đã cắt để huấn luyện bài toán **Nhận diện ký tự** (OCR).

## 🛠 Hướng dẫn cài đặt
Sau khi tải các tệp `.zip` trên, bạn cần giải nén vào đúng cấu trúc thư mục sau để mã nguồn có thể nhận diện:

```text
data/
└── training/
    ├── yolo_plate_dataset/       # Giải nén yolo_plate_dataset.zip vào đây
    └── yolo_plate_ocr_dataset/   # Giải nén yolo_plate_ocr_dataset.zip vào đây
```