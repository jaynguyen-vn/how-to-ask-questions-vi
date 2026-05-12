# Cách Hỏi Để Người Khác Muốn Giúp

> Bản viết lại tiếng Việt hiện đại của bài kinh điển  
> **["How To Ask Questions The Smart Way"](http://www.catb.org/~esr/faqs/smart-questions.html)**  
> của Eric S. Raymond & Rick Moen.

Một trang HTML tĩnh, đơn file, phong cách hacker terminal — viết cho lập trình viên nói tiếng Việt khi tham gia cộng đồng kỹ thuật quốc tế (Stack Overflow, GitHub, Discord…).

## Vì sao có bản này?

Bài gốc của ESR đã định hình văn hóa hỏi-đáp kỹ thuật trong hơn 20 năm, nhưng:

- Ví dụ trong bài gốc dùng Usenet, IRC — hiện đã hiếm dùng.
- Văn phong gốc dày đặc, khó tiếp cận với người mới đọc tiếng Anh kỹ thuật.
- Cần một bản tiếng Việt **viết lại** (không phải dịch máy) cho thời Discord/GitHub/Stack Overflow/LLM.

Bản này tôn trọng tinh thần và bản quyền của tác phẩm gốc — không thay thế, chỉ làm cầu nối cho dev Việt.

## Tính năng

- Single HTML file, không build, mở trực tiếp trong trình duyệt.
- Sidebar TOC sticky, highlight section đang đọc.
- 12 section đầy đủ: từ "AI giúp gì, khi nào hỏi người khác" → "Cách trả lời câu hỏi".
- Ví dụ Bad/Good thực tế: React, Postgres…
- Responsive: desktop, tablet, mobile.
- Dark mode mặc định, phong cách hacker terminal.

## Sử dụng

Mở trực tiếp:

```bash
open index.html
```

Hoặc serve static:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy lên GitHub Pages

1. Push repo lên GitHub.
2. Vào **Settings → Pages → Source**: chọn branch `main`, folder `/ (root)`.
3. Truy cập: `https://<username>.github.io/<repo-name>/`.

## Đóng góp

PR và issue luôn được hoan nghênh:

- Sửa lỗi chính tả, ngữ pháp.
- Đề xuất ví dụ Việt-hóa tốt hơn.
- Cải thiện UI/UX/accessibility.
- Dịch sang ngôn ngữ khác (tách branch riêng).

## Bản quyền

- **Bài gốc**: © Eric S. Raymond & Rick Moen — theo [copying policy](http://www.catb.org/~esr/) tại catb.org.
- **Bản viết lại tiếng Việt**: phi lợi nhuận, miễn phí cho mọi mục đích phi thương mại.

## Tài nguyên liên quan

- [Bài gốc — How To Ask Questions The Smart Way](http://www.catb.org/~esr/faqs/smart-questions.html)
- [Stack Overflow: How do I ask a good question?](https://stackoverflow.com/help/how-to-ask)
- [Minimal Reproducible Example (MRE)](https://stackoverflow.com/help/minimal-reproducible-example)
- [The XY Problem](https://xyproblem.info/)
- [Don't Ask To Ask, Just Ask](https://dontasktoask.com/)
- [No Hello Club](https://nohello.club/)

---

```
┌─────────────────────────────────────────────┐
│  ask better → get better answers → repeat   │
└─────────────────────────────────────────────┘
```
