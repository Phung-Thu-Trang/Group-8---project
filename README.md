# 📊 Group-8 Project: Global Cybersecurity Threats

## 💡 Mô tả dự án

Dự án này được xây dựng bằng Python với mục tiêu phân tích dữ liệu liên quan đến các mối đe dọa an ninh mạng toàn cầu, từ đó trực quan hóa và rút ra những insight quan trọng.

Dự án bao gồm các bước chính:
- ✅ Đặt vấn đề & xác định mục tiêu
- ✅ Làm sạch và xử lý dữ liệu gốc
- ✅ Phân tích & trực quan hóa kết quả

> 🔧 **Công nghệ sử dụng**: Python, Pandas, Matplotlib, Seaborn, Jupyter Notebook

---

## 🏗️ Cấu trúc thư mục
```
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
```
---

## 🚀 Cách chạy dự án

### 1. Clone Repository
Mở terminal hoặc command prompt và chạy lệnh sau:

```
git clone https://github.com/Phung-Thu-Trang/Group-8---project.git
cd Group-8---project
```

### 2. Cài đặt các thư viện cần thiết
Cài đặt tất cả các thư viện được liệt kê trong file requirements.txt:
```bash
pip install -r requirements.txt
```

### 3. Chạy Jupyter Notebook trong Visual Studio Code
Nếu bạn sử dụng VS Code làm môi trường phát triển, bạn có thể chạy các file .ipynb một cách trực tiếp mà không cần dùng lệnh jupyter notebook. Làm theo các bước sau:

⚙️ Cài đặt yêu cầu
Mở VS Code.

Cài đặt extension "Jupyter" (của Microsoft) nếu chưa có:

Vào Extensions (Ctrl + Shift + X)

Tìm "Jupyter" và bấm Install.

Đảm bảo bạn đã cài ipykernel trong môi trường Python hiện tại:
```
pip install ipykernel
```
▶️ Chạy notebook
Mở file .ipynb trong thư mục notebooks/ bằng cách click đúp trong trình duyệt file của VS Code.

Ở đầu mỗi ô (cell), bạn sẽ thấy nút ▶️ (Run Cell). Bấm vào đó để chạy từng cell.

Bạn cũng có thể bấm Run All để chạy toàn bộ notebook.

📍 Thứ tự chạy:

00-problem-statement.ipynb: Đặt vấn đề và mục tiêu.

01-data-clearing.ipynb: Làm sạch dữ liệu. Dữ liệu sạch sẽ được lưu ở data/processed/.

02-analysis.ipynb: Thực hiện phân tích và trực quan hóa dữ liệu đã làm sạch.

## 📈 Kết quả 
- ✅ Thống kê số lượng cuộc tấn công theo năm
- ✅ Thống kê phần trăm các loại hình tấn công
- ✅ Thống kê số lượng cuộc tấn công theo quốc gia trong vòng 10 năm
- ✅ Thống kê thiệt hại tài chính theo ngành
- ✅ Thống kê thiệt hại tài chính và số người bị ảnh hưởng theo năm
- ✅ Thống kê tỷ lệ phần trăm lỗ hổng bảo mật trong các cuộc tấn công
- ✅ Thống kê số lượng cuộc tấn công theo lỗ hổng bảo mật
- ✅ Thống kê thiệt hại theo loại lỗ hổng bảo mật
- ✅ Thống kê số lượng cuộc tấn công theo lỗ hổng bảo mật Zero-day
- ✅ Thống kê cơ chế phòng thủ được sử dụng cho từng loại lỗ hổng bảo mật



