# TeamRAG

Nền tảng RAG đa người dùng, cho phép tạo nhóm riêng và trò chuyện với tài liệu.

## Cấu trúc

- `backend/` — NestJS REST API, kết nối PostgreSQL & Qdrant
- `frontend/` — Next.js App Router, Tailwind + shadcn UI

## Phát triển

```bash
# Chạy backend
cd backend
npm run start:dev

# Chạy frontend
cd ../frontend
npm run dev