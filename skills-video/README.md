# Video kỹ năng — Bùi Tuấn Dũng

Remotion 4.0.539, React 19. Video 25 giây, 30 fps, không âm thanh.

- Desktop: 1280 × 720. Mobile: 720 × 1080.
- `npm ci` cài dependencies.
- `npm run dev -- --no-open` mở Remotion Studio.
- `npm run build:embed` cập nhật `../dist/skills-film.js`.
- `npx tsc --noEmit` kiểm tra TypeScript.

`src/SkillsFilm.tsx` chứa timeline; từng cảnh nằm trong file riêng. `src/Root.tsx` đăng ký cả hai bố cục và từng cảnh. `src/embed.tsx` nhúng Player vào phần Kỹ năng, có phát/dừng, tua, chọn cảnh và xem lại. `dist/skills-film-loader.js` chỉ tải trình phát khi cuộn gần tới; danh sách kỹ năng vẫn đọc được bên dưới.
