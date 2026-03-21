# 📊 Bộ dữ liệu huấn luyện (Training Dataset)

Thư mục này chứa các tệp tin hướng dẫn và dữ liệu mẫu (Sample) nhằm giúp bạn hình dung cấu trúc dữ liệu trước khi tải bộ dữ liệu đầy đủ.

## 📥 Tải xuống dữ liệu đầy đủ
Do giới hạn dung lượng, dữ liệu thực tế được lưu trữ tập trung tại Google Drive:

* **Link Google Drive:** [License-Plate](https://drive.google.com/drive/folders/14N8wrz-H5rJgPeBCskf4jlIp0dH_Sage?usp=sharing)
* **Tổng dung lượng:** ~452 MB
* **Chi tiết các gói dữ liệu:**
    * `lpd-dataset` (~333.3 MB): Chứa hình ảnh và nhãn (label) phục vụ bài toán **Phát hiện biển số xe**.
    * `lpr-dataset` (~118.6 MB): Chứa dữ liệu ký tự đã cắt để huấn luyện bài toán **Nhận diện ký tự**.
* **Lưu ý:** Làm bước nào thì sử dụng lần lượt đúng gói đó.

## 🛠 Hướng dẫn cài đặt
Sau khi tải về, bạn sẽ nhận được đúng cấu trúc thư mục thế này:

```text
~/
├── images/
│   ├── train/
│   └── val/
└── labels/
    ├── train/
    └── val/
```