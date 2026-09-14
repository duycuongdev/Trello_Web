# 📝 Trello Web

Một ứng dụng web lấy cảm hứng từ Trello, được xây dựng bằng hệ sinh thái React hiện đại và Material UI. Ứng dụng cung cấp giao diện trực quan và các tính năng kéo thả (drag and drop) mượt mà để quản lý công việc hiệu quả.

---

## 🚀 Công nghệ sử dụng

- **Core:** React 18, Vite
- **UI Framework:** Material UI (MUI v5)
- **Drag & Drop:** `@dnd-kit` (Core, Sortable, Utilities)
- **State Management:** Redux Toolkit & Redux Persist
- **Routing:** React Router v6
- **Data Fetching:** Axios
- **Form Handling:** React Hook Form
- **Notifications:** React Toastify
- **Utils:** Lodash, tsParticles

---

## 📦 Yêu cầu môi trường

- Node.js >= 18.x
- Yarn hoặc npm

---

## 🛠️ Cài đặt và Chạy dự án

1. **Clone dự án**
   ```bash
   git clone <your-repo-url>
   cd trello-web
   ```

2. **Cài đặt dependencies**
   ```bash
   yarn install
   # hoặc npm install
   ```

3. **Cấu hình biến môi trường**
   Tạo file `.env` ở thư mục gốc (hoặc copy từ `.env.example` nếu có) và cấu hình các biến cần thiết (ví dụ: VITE_API_URL, ...).

4. **Chạy server phát triển (Development)**
   ```bash
   yarn dev
   # hoặc npm run dev
   ```
   Ứng dụng sẽ chạy tại: `http://localhost:5173`

5. **Build cho Production**
   ```bash
   yarn build
   # hoặc npm run build
   ```
   Kết quả build sẽ nằm trong thư mục `dist/`.

6. **Kiểm tra Lint (Code Quality)**
   ```bash
   yarn lint
   # hoặc npm run lint
   ```

---

## 📁 Cấu trúc thư mục (Gợi ý)

```text
trello-web/
├── public/
├── src/
│   ├── assets/        # Hình ảnh, icons, ...
│   ├── components/    # Các UI component dùng chung
│   ├── pages/         # Các trang chính (Board, Auth, ...)
│   ├── redux/         # Setup Redux Toolkit (slices, store)
│   ├── router/        # Cấu hình routing
│   ├── services/      # Giao tiếp API bằng Axios
│   ├── utils/         # Các hàm tiện ích
│   ├── App.jsx
│   └── main.jsx
├── .env
├── vite.config.js
└── package.json
```

---

## 🧑‍💻 Tác giả

- **Duy Cuong** 

---

## 📜 Giấy phép

Dự án sử dụng giấy phép MIT.
