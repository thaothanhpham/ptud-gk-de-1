
## 📌 Thông tin cá nhân  
- **Họ tên**: Phạm Thanh Thảo  
- **Mã sinh viên**: 22695701
---

## 📌 Mô tả project  
# Blog với Chức năng Bình luận

## 1. Giới thiệu
Đây là một dự án blog đơn giản được xây dựng bằng Flask, hỗ trợ hai tác nhân (actor, user) với chức năng bình luận (comment). Các bài viết có hiển thị hình ảnh ngẫu nhiên từ [Picsum Photos](https://picsum.photos/).

## 2. Yêu cầu
### a. Tạo project trên GitHub
- **Tên repository:** `ptud-gk-de-1`
- **File Readme.MD:** Chứa thông tin cá nhân và hướng dẫn cài đặt project.

### b. Chức năng chính
- Hiển thị danh sách bài viết.
- Hỗ trợ người dùng bình luận dưới mỗi bài viết.
- Hình ảnh bài viết được lấy ngẫu nhiên từ [Picsum Photos](https://picsum.photos/).

## 3. Cài đặt
### 3.1. Yêu cầu hệ thống
- Python 3.8+.
- Flask.
- SQLite (hoặc PostgreSQL nếu triển khai thực tế).
- Các thư viện khác được liệt kê trong `requirements.txt`.

### 3.2. Hướng dẫn cài đặt
#### Bước 1: Clone repository
```sh
git clone https://github.com/thaothanhpham/ptud-gk-de-1.git
cd ptud-gk-de-1
```
#### Bước 2: Tạo môi trường ảo và cài đặt dependencies

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
#### Bước 5: Chạy ứng dụng
```sh
python app.py
```
Mở trình duyệt và truy cập `http://127.0.0.1:5000/` 
                            http://172.20.10.9:5000/
để xem blog.

## 4. Hình ảnh minh họa
Bài viết hiển thị với hình ảnh ngẫu nhiên từ [Picsum Photos](https://picsum.photos/):

![Demo](https://picsum.photos/600/300)

