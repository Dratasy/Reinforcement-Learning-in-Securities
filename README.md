# Tên Dự Án

## 1. Giới thiệu
Đây là một cách tiếp cận khác với bài toán dự đoán xu hướng giá cổ phiếu. Cách tiếp cận truyền thống là sử dụng Học giám sát với các mô hình CNN, LSTM, GNN để dự đoán đầu ra là xu hướng giá. Trong bài toán này, tôi sẽ dùng Reinforcement Learning với việc thiết kế hàm phần thưởng để đạt được độ chính xác dự đoán xu hướng giá tốt hơn.

## 2. Cấu trúc thư mục
Cấu trúc thư mục của dự án như sau:
- **agents**: định nghĩa agent của một mô hình RL
- **configs**: tùy chỉnh config
- **data**: chứa dữ liệu huấn luyện và kiểm thử
- **data_loaders**: tiền xử lý dữ liệu
- **environments**: mô phỏng lại môi trường giao dịch
- **executors**: định nghĩa cách huấn luyện mô hình
- **notebooks**: chứa notebook sử dụng trong dự án
- **results**: lưu trữ kết quả huấn luyện và kiểm thử
- **utils**: chứa các files khác

## 3. Cài đặt và Hướng dẫn sử dụng
### 3.1 Clone repository:
```bash
git clone [link repo](https://github.com/Dratasy/Reinforcement-Learning-in-Securities.git)
cd [Reinforcement-Learning-in-Securities]
```
### 3.2 Cài đặt dependencies
```bash
conda env create -f environment.yml
```
### 3.3 Chạy dự án:
```bash
python main.py
```
## 4. Thực nghiệm và kết quả
### 4.1 Tập dữ liệu

### 4.2 Kết quả thí nghiệm

