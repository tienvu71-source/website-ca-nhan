# website-ca-nhan

Website thương hiệu cá nhân. Framework chưa chọn, chờ đặc tả.

- Node: xem `.nvmrc`
- Deploy: Vercel (kết nối GitHub)

## Chạy local

```bash
npm install
npm run dev      # http://localhost:4321
npm run build    # xuất ra thư mục dist/
```

## Chỉnh nội dung

- Thông tin thương hiệu (tên, liên hệ, tên miền): `src/config.ts`
- Bài viết: thêm file `.md` vào `src/content/blog/` (có `title`, `description`, `date`, `category`; `draft: true` để ẩn)
- Trang: `src/pages/`; giao diện: `src/styles/global.css`
- 3 bài hiện tại là bài mẫu, cần thay bằng nội dung thật.
