# ☁️ LAB2 — Cloud PaaS Demo with Streamlit

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Cloud](https://img.shields.io/badge/Platform-PaaS-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

**Ứng dụng web đơn giản minh hoạ mô hình điện toán đám mây PaaS (Platform as a Service)**  
*Built with ❤️ using Python & Streamlit*

[🚀 Demo Live](#) • [📖 Docs](#cài-đặt) • [🐛 Report Bug](#)

</div>

---

## 📌 Giới thiệu

Dự án này được xây dựng trong khuôn khổ **LAB 2 - Cloud Computing**, nhằm minh hoạ cách triển khai một ứng dụng web trên nền tảng **PaaS (Platform as a Service)** sử dụng **Streamlit Cloud**.

> 💡 Với PaaS, developer chỉ cần tập trung viết code — không cần lo về máy chủ, hệ điều hành hay hạ tầng bên dưới.

---

## ✨ Tính năng

- ✅ Giao diện web tương tác không cần HTML/CSS
- ✅ Nhập tên và nhận lời chào cá nhân hoá
- ✅ Minh hoạ triển khai ứng dụng trên nền tảng PaaS
- ✅ Chạy được cả local lẫn trên Streamlit Cloud

---

## 🛠️ Công nghệ sử dụng

| Công nghệ | Vai trò |
|-----------|---------|
| **Python** | Ngôn ngữ lập trình chính |
| **Streamlit** | Framework xây dựng giao diện web |
| **Streamlit Cloud** | Nền tảng PaaS để triển khai ứng dụng |

---

## 📁 Cấu trúc dự án

```
LAB2_paas_streamlit/
├── app.py               # File chính của ứng dụng
├── requirements.txt     # Danh sách thư viện cần thiết
└── README.md            # Tài liệu hướng dẫn (file này)
```

---

## ⚙️ Cài đặt

### Yêu cầu
- Python 3.10+
- pip

### Chạy local

```bash
# 1. Clone repo về máy
git clone https://github.com/your-username/LAB2_paas_streamlit.git
cd LAB2_paas_streamlit

# 2. Cài thư viện
pip install -r requirements.txt

# 3. Chạy ứng dụng
streamlit run app.py
```

Truy cập tại: `http://localhost:8501`

### Truy cập từ điện thoại (cùng mạng WiFi)

Sau khi chạy, terminal sẽ hiện:
```
Local URL:   http://localhost:8501
Network URL: http://192.168.x.x:8501  ← dùng cái này trên điện thoại
```

---

## 🌐 Triển khai lên Streamlit Cloud (PaaS)

1. Push code lên **GitHub**
2. Truy cập [streamlit.io/cloud](https://streamlit.io/cloud)
3. Đăng nhập bằng tài khoản GitHub
4. Chọn repo → chọn `app.py` → bấm **Deploy**
5. Streamlit Cloud sẽ tự động cài `requirements.txt` và chạy ứng dụng

> Đây chính là sức mạnh của **PaaS** — deploy chỉ với vài click, không cần cấu hình server! 🎉

---

## 🧠 Kiến thức liên quan

<details>
<summary><b>PaaS là gì?</b></summary>

**PaaS (Platform as a Service)** là mô hình điện toán đám mây cung cấp nền tảng sẵn sàng để developer triển khai ứng dụng mà không cần quản lý hạ tầng bên dưới (máy chủ, OS, network...).

| Mô hình | Developer quản lý |
|---------|------------------|
| IaaS | OS, Runtime, App |
| **PaaS** | **Chỉ App & Data** |
| SaaS | Không cần quản lý |

</details>

<details>
<summary><b>Tại sao dùng Streamlit Cloud?</b></summary>

- Miễn phí cho project nhỏ
- Tự động deploy khi push code lên GitHub
- Không cần cấu hình server hay Docker
- Đây là ví dụ điển hình của PaaS

</details>

---

## 👨‍💻 Tác giả

**[Tên của bạn]**  
📧 email@example.com  
🔗 [GitHub](https://github.com/your-username)

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<div align="center">
  <sub>⭐ Nếu thấy hữu ích, hãy cho một star nhé!</sub>
</div>
