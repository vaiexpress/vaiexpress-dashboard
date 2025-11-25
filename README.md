# VAIexpress Node API

Express backend สำหรับระบบขนส่งไทย–ลาว เชื่อม MySQL (ฐาน `vaiexpress`) และพร้อม deploy ไป Render

## Scripts
- `npm install`
- `npm start` (port จาก `.env` หรือ 4000)

## Env
- `DB_URL` (เช่น `mysql://user:pass@host:3306/vaiexpress`) **หรือ** `DB_HOST`, `DB_USER`, `DB_PASS`, `DB_NAME`
- `PORT` (Render จะตั้งให้เอง)

## API หลัก
- `GET /health`
- `GET /api/stats/summary`
- `GET /api/orders?limit=50`
- `GET /api/orders/:id`
- `POST /api/orders`
- `PUT /api/orders/:id`
- `DELETE /api/orders/:id`

## Deploy
ดูขั้นตอนละเอียดใน `README_RENDER.md` (Render free tier)
