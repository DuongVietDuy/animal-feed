# 🐮 Feed Store App - Web bán thức ăn chăn nuôi

Ứng dụng web giúp người dùng dễ dàng xem, đặt mua các loại thức ăn chăn nuôi (bò, heo, gà...) và hỗ trợ quản lý sản phẩm, đơn hàng cho quản trị viên.

---

## 📌 Mục lục

- [🎯 Mục tiêu](#-mục-tiêu)
- [🚀 Tính năng](#-tính-năng)
- [🛠 Công nghệ sử dụng](#-công-nghệ-sử-dụng)
- [📁 Cấu trúc thư mục](#-cấu-trúc-thư-mục)
- [🧑‍💻 Cài đặt và chạy project](#-cài-đặt-và-chạy-project)
- [🔒 Phân quyền người dùng](#-phân-quyền-người-dùng)
- [📸 Giao diện (screenshots)](#-giao-diện-screenshots)
- [📞 Liên hệ](#-liên-hệ)

---

## 🎯 Mục tiêu

- Cung cấp nền tảng thương mại điện tử cho ngành chăn nuôi.
- Quản lý sản phẩm, khách hàng, đơn hàng.
- Giao diện thân thiện, dễ sử dụng cho cả người dùng và quản trị viên.

---

## 🚀 Tính năng

- 🛒 Xem và đặt mua sản phẩm
- 🔐 Đăng ký, đăng nhập người dùng
- 👤 Quản lý người dùng (admin)
- 📦 Quản lý sản phẩm và đơn hàng
- 🖼 Upload ảnh sản phẩm
- 💬 Liên hệ hỗ trợ

---

## 🛠 Công nghệ sử dụng

### Frontend:
- ReactJS
- React Router DOM
- Axios
- Bootstrap hoặc TailwindCSS

### Backend:
- Node.js + Express
- MongoDB + Mongoose
- Multer (upload ảnh)
- JWT (xác thực người dùng)
- Dotenv, CORS

---

## 📁 Cấu trúc thư mục

```
feed-store-app/
├── backend/
│   ├── src/
│   │   ├── config/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── uploads/
│   │   └── index.js
│   ├── .env
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── routers/
│   │   ├── services/
│   │   ├── utils/
│   │   ├── App.js
│   │   └── index.js
│   └── package.json
```

---

## 🧑‍💻 Cài đặt và chạy project

### 1. Clone project

```bash
git clone https://github.com/yourusername/feed-store-app.git
cd feed-store-app
```

### 2. Backend

```bash
cd backend
npm install
```

Tạo file `.env` với nội dung:

```
PORT=5000
MONGO_URI=mongodb+srv://<user>:<password>@cluster.mongodb.net/feedstore
JWT_SECRET=your_jwt_secret
```

Chạy server:

```bash
npm start
```

### 3. Frontend

```bash
cd ../frontend
npm install
npm start
```

Truy cập ứng dụng tại: `http://localhost:3000`

---

## 🔒 Phân quyền người dùng

| Vai trò   | Quyền                              |
|-----------|------------------------------------|
| User      | Xem và đặt hàng sản phẩm           |
| Admin     | Quản lý sản phẩm, đơn hàng, người dùng |

---

## 📸 Giao diện (screenshots)

> *(Thêm ảnh chụp màn hình sau khi hoàn thành frontend)*

---

## 📞 Liên hệ

- 💼 Tác giả: Nguyễn Văn A *(sửa theo tên của bạn)*
- 📧 Email: nguyenvana@example.com *(sửa email của bạn)*
- 🌐 Website: [chưa có]

---