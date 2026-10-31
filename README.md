# folioscape-site

Trang giới thiệu, chính sách quyền riêng tư và hỗ trợ của game Folioscape (iPhone), phục vụ bằng GitHub Pages từ nhánh
`main` (không dùng GitHub Actions). Địa chỉ: https://nguyenvanlamm.github.io/folioscape-site/

- `index.html`: trang giới thiệu (tiếng Anh), có thẻ OG/Twitter và JSON-LD (WebSite, VideoGame/MobileApplication).
- `privacy.html`: Privacy Policy URL cho App Store Connect.
- `support.html`: Support URL cho App Store Connect.
- `sitemap.xml`, `robots.txt` (cho phép mọi bot, kể cả bot AI), `llms.txt` (tóm tắt game cho AI).
- `assets/`: icon (gốc 1024, `icon-96.png` cho logo, `apple-touch-icon.png` 180), ảnh màn chơi (`screen-game.webp` hiển thị
  trên trang, `screen-game.png` gốc cho JSON-LD), ảnh chia sẻ `share-card.png` 1200×630, font Young Serif và Figtree
  (OFL, giấy phép kèm theo trong `assets/fonts/`).

Lưu ý: với project site trên GitHub Pages, bot đọc `robots.txt` ở gốc `nguyenvanlamm.github.io`, nên cần thêm
`folioscape-site` vào `robots.txt` và `llms.txt` của repo `nguyenvanlamm.github.io`.
