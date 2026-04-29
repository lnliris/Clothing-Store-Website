# Clothing Store (FE + BE)

Monorepo cho ứng dụng Clothing Store gồm:
- `fe/`: Frontend (React + Ant Design)
- `be/`: Backend (Spring Boot + MongoDB Atlas + VNPay)

## Cấu trúc repo

```text
.
├─ fe/   # Web client
└─ be/   # REST API / business logic
```

## Chạy nhanh

### 1) Frontend (`fe/`)

1. Mở terminal tại thư mục `fe/`
2. Cài dependency:

```bash
cd fe
npm install
```

3. Chạy dev server:

```bash
npm run dev
```

> Mặc định Vite thường chạy tại `http://localhost:5173`. (Bạn có thể kiểm tra port trong log khi chạy.)

### 2) Backend (`be/`)

1. Mở terminal tại thư mục `be/`
2. Chạy bằng Gradle:

```bash
cd be
./gradlew bootRun
```

> Backend mặc định chạy tại `http://localhost:8080`.

## Cấu hình môi trường

Do mỗi dự án có cấu hình riêng, vui lòng xem thêm:
- `fe/README.md` (thường liên quan đến biến môi trường cho API URL)
- `be/README.md` (thông tin chạy Spring Boot và MongoDB Atlas)

## Tài liệu chi tiết

Xem thêm trong:
- `fe/README.md`
- `be/README.md`

