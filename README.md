# 🎬 Hybrid-Movie-Rating-Prediction-and-Recommendation-System

Xây dựng hệ thống gợi ý phim dựa trên dữ liệu đánh giá của người dùng.  
Dự án được thực hiện toàn bộ trong một file Jupyter Notebook duy nhất, với các phân tích, mô hình dự đoán và giải thích rõ ràng.

---

## 📌 **Mục tiêu dự án**

- Tổng hợp và phân tích dữ liệu:
  - Tương quan giữa điểm đánh giá và số lượt đánh giá.
  - Phân bố số lượng phim theo thể loại.
  - Mối quan hệ giữa số lượt đánh giá với thể loại phim dựa trên giới tính người dùng.

- Xây dựng mô hình dự đoán điểm số:
  - **Random Forest** để dự đoán điểm số.
  - Các mô hình **Collaborative Filtering (CF)**:
    - SVD
    - SlopeOne
    - KNNBasic
  - So sánh kết quả 3 mô hình CF, chọn mô hình tốt nhất để tạo bảng xếp hạng top phim.

- Kết hợp mô hình:
  - Sử dụng Random Forest đối với các cold-start, ngược lại dùng CF.
  - Sử dụng trọng số cho RF và CF từ việc xác định mức độ "mới" của người dùng và phim ảnh để tăng độ chính xác của dự án.

---

## 📁 **Cấu trúc thư mục**
<pre> ```
  ├── Documents
  ├── data/
  │ ├── file1.csv
  │ ├── file2.csv
  │ ├── file3.csv
  │ └── file4.csv
  ├── MLcuoiky.ipynb
  ├── README.md
  └── library.txt 
  ``` </pre>

- `Documents`: Chứa báo cáo và slide thuyết trình của dự án.
- `data/`: Chứa dữ liệu CSV sử dụng trong dự án.
- `MLcuoiky.ipynb`: File chính với toàn bộ code và phân tích.
- `library.txt`: Danh sách thư viện cần cài đặt.
- `README.md`: Mô tả dự án.

---

## ⚙️ Sử dụng

- Clone repo về máy
- Cài các thư viện trong `library.txt`
- Mở `MLcuoiky.ipynb` bằng Jupyter Notebook để chạy

---

## 📝 Tác giả

- **Mai Đình Đức Trung**
- [DucTrung184](hhttps://github.com/DucTrung184)
