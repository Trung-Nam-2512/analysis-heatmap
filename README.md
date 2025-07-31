# 📊 Correlation Heatmap Analysis - Workspace Sạch

## 📁 Files trong Workspace

### ✅ **Files cần thiết:**

- `4_stations_31_7.xlsx` - File dữ liệu Excel gốc
- `requirements.txt` - Danh sách thư viện cần thiết

- `heatmap_env/` - Virtual environment
- `README.md` - File hướng dẫn này

## 🚀 Cách sử dụng

### 1. **Cài đặt môi trường:**

```bash
# Tạo virtual environment
python -m venv heatmap_env

# Kích hoạt virtual environment
# Windows:
heatmap_env\Scripts\activate
# Linux/Mac:
source heatmap_env/bin/activate

# Cài đặt thư viện
pip install -r requirements.txt
```

### 2. **Chạy phân tích:**

```bash
# Khởi động Jupyter Notebook
jupyter notebook
```

### 3. **Sử dụng hướng dẫn:**

- Mở file `JUPYTER_STEP_BY_STEP_GUIDE.md`
- Copy từng bước vào Jupyter Notebook
- Chạy từng cell theo thứ tự

## 📋 Yêu cầu phân tích

### 🎯 **Yêu cầu 1: Lagged Time Analysis**

- Phân tích lag từ 1-30 ngày
- Tìm thời gian có tương quan tốt nhất
- Vẽ biểu đồ lag correlation

### 🎯 **Yêu cầu 2: Statistical Correlation Analysis**

- Tính min, max, mean và các thống kê khác
- So sánh tương quan giữa các thống kê
- Vẽ heatmap tương quan thống kê

## 📊 Kết quả sẽ có

- **Lagged time analysis** với lag tốt nhất cho từng cặp biến
- **Statistical correlation analysis** với tương quan giữa min, max, mean
- **Multiple visualizations** (heatmaps, line plots)
- **Comprehensive results** với insights chi tiết

## 🔧 Thư viện cần thiết

- pandas >= 1.3.0
- numpy >= 1.21.0
- matplotlib >= 3.4.0
- seaborn >= 0.11.0
- openpyxl >= 3.0.0
- xlrd >= 2.0.0
- jupyter >= 1.0.0
- notebook >= 6.4.0
- scipy >= 1.13.0
