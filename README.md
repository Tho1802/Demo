<div align="center">

# 📧 PHISHING EMAIL DETECTION SYSTEM  
### 🚀 Hệ Thống Phát Hiện Email Lừa Đảo Bằng Deep Learning (LSTM)

![Python](https://img.shields.io/badge/Python-3.8-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange)
![Gradio](https://img.shields.io/badge/Gradio-WebApp-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

</div>

---

## 📌 Giới thiệu

Hệ thống phát hiện email lừa đảo (Phishing Detection) sử dụng mô hình **Deep Learning – LSTM** để phân loại email thành:

- ⚠️ Email Lừa Đảo (Phishing)
- ✅ Email An Toàn (Safe)

Ứng dụng được triển khai dưới dạng **Web App** bằng Gradio và có thể chạy online trên HuggingFace.

---

### 📥 Nhập nội dung email

<p align="center">
<img src="https://raw.githubusercontent.com/gradio-app/gradio/main/demo/hello_world/screenshot.png" width="600">
</p>

---

### 📊 Biểu đồ xác suất dự đoán

- Hiển thị xác suất Phishing vs Safe
- Tính theo mô hình LSTM
- Độ tin cậy hiển thị %

---

## 🧠 Công nghệ sử dụng

|  Thành phần   |       Công nghệ      |
|---------------|----------------------|
| Ngôn ngữ      | Python               |
| Deep Learning | TensorFlow / Keras   |
| Mô hình       | LSTM                 |
| Giao diện Web | Gradio               |
| Biểu đồ       | Matplotlib           |

---

## ⚙️ Quy trình xử lý

1️⃣ Tiền xử lý văn bản (lowercase)  
2️⃣ Tokenizer chuyển văn bản → chuỗi số  
3️⃣ Padding (max_len = 150)  
4️⃣ LSTM dự đoán xác suất  
5️⃣ Hiển thị kết quả & biểu đồ  

---

## 📂 Cấu trúc thư mục
project/
│
├── app.py
├── model.h5
├── tokenizer.pkl
├── requirements.txt
└── README.md

---

## 🚀 Chạy ứng dụng Local

Cài đặt thư viện:
pip install -r requirements.txt

Chạy ứng dụng:
python app.py

---

## 🌐 Deploy HuggingFace

Ứng dụng có thể triển khai tại:

👉 https://huggingface.co/spaces

Chỉ cần upload:

- app.py
- model.h5
- tokenizer.pkl
- requirements.txt

---

## 📊 Kết quả đạt được

- Phân loại chính xác email lừa đảo
- Giao diện web trực quan
- Hiển thị biểu đồ xác suất
- Lưu lịch sử kiểm tra

---

## 🎯 Mục tiêu phát triển tương lai

- Phân loại 3 lớp (Spam / Phishing / Safe)
- Tích hợp API
- Dashboard thống kê nâng cao
- Kết nối hệ thống email thực tế

---
