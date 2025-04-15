# 📊 Group-8 Project: Global Cybersecurity Threats

## 💡 Mô tả dự án

Dự án này được xây dựng bằng Python với mục tiêu phân tích dữ liệu lớn liên quan đến các mối đe dọa an ninh mạng toàn cầu, từ đó trực quan hóa và rút ra những insight quan trọng.

Dự án bao gồm các bước chính:
- ✅ Đặt vấn đề & xác định mục tiêu
- ✅ Làm sạch và xử lý dữ liệu gốc
- ✅ Phân tích & trực quan hóa kết quả

> 🔧 **Công nghệ sử dụng**: Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

---

## 🏗️ Cấu trúc thư mục
Group-8---project/
├── 📁 data/                        # Thư mục chứa dữ liệu
│   ├── 📁 raw/                     # Dữ liệu gốc ban đầu
│   │   ├── Global_Cybersecurity_Threats_2021.csv
│   │   └── Problem_Statement.xlsx
│   └── 📁 processed/               # Dữ liệu đã được làm sạch
│       └── Cleaned_Global_Cybersecurity_Threats.csv
│
├── 📁 notebooks/                  # Các file Jupyter Notebook xử lý & phân tích
│   ├── 00-problem-statement.ipynb   # Đặt vấn đề
│   ├── 01-data-clearing.ipynb       # Xử lý, làm sạch dữ liệu
│   └── 02-analysis.ipynb            # Phân tích & trực quan hóa dữ liệu
│
├── README.md                     # Tài liệu mô tả dự án
└── requirements.txt             # Danh sách thư viện cần cài

---

## 🚀 Cách chạy dự án

### 1. Clone Repository
Mở terminal hoặc command prompt và chạy lệnh sau:

```bash
git clone https://github.com/Phung-Thu-Trang/Group-8---project.git
cd Group-8---project
```

### 2. Tạo Môi trường ảo (Khuyến nghị)
Khuyến khích sử dụng môi trường ảo để tránh xung đột thư viện:

```bash
# Lệnh cho Linux/macOS
python3 -m venv venv
source venv/bin/activate

# Lệnh cho Windows
python -m venv venv
.\venv\Scripts\activate
```

### 3. Cài đặt các thư viện cần thiết
Cài đặt tất cả các thư viện được liệt kê trong file requirements.txt:
```bash
pip install -r requirements.txt
```

### 4. Chạy Jupyter Notebook
Khởi động Jupyter Notebook từ terminal:

```bash
jupyter notebook
```
Trình duyệt web của bạn sẽ mở ra giao diện Jupyter. Điều hướng đến thư mục notebooks/ và mở các file theo thứ tự sau để thực hiện quy trình phân tích:

00-problem-statement.ipynb: Đặt vấn đề và mục tiêu.
01-data-clearing.ipynb: Chạy notebook này để thực hiện quá trình làm sạch dữ liệu. Dữ liệu đã làm sạch sẽ được lưu vào data/processed/.
02-analysis.ipynb: Chạy notebook này để thực hiện phân tích và xem các trực quan hóa dựa trên dữ liệu đã được làm sạch.

## 📈 Kết quả & Insight chính
- ✅ Thống kê số lượng cuộc tấn công theo năm
- ✅ Thống kê phần trăm các loại hình tấn công
- ✅ Thống kê số lượng cuộc tấn công theo quốc gia trong vòng 10 năm
...
