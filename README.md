# Cách Hỏi Để Người Khác Muốn Giúp

> Hướng dẫn tiếng Việt dựa trên bài kinh điển  
> **["How To Ask Questions The Smart Way"](http://www.catb.org/~esr/faqs/smart-questions.html)**  
> của Eric S. Raymond & Rick Moen.

Một trang HTML tĩnh, đơn file, phong cách hacker terminal — viết cho lập trình viên nói tiếng Việt khi tham gia cộng đồng kỹ thuật quốc tế (Stack Overflow, GitHub, Discord…).

## Vì sao có bản này?

Bài gốc của ESR đã định hình văn hóa hỏi-đáp kỹ thuật trong hơn 20 năm, nhưng:

- Ví dụ trong bài gốc dùng Usenet, IRC — hiện đã hiếm dùng.
- Văn phong gốc dày đặc, khó tiếp cận với người mới đọc tiếng Anh kỹ thuật.
- Cần một hướng dẫn tiếng Việt (không phải dịch máy) bàn lại các ý chính cho thời Discord/GitHub/Stack Overflow/LLM.

Bản này tôn trọng tinh thần và bản quyền của tác phẩm gốc — không thay thế, chỉ làm cầu nối cho dev Việt.

## Tính năng

- Single HTML file, không build, mở trực tiếp trong trình duyệt.
- Sidebar TOC sticky, highlight section đang đọc.
- 16 mục: tóm tắt 30 giây, trước khi hỏi, chọn nơi hỏi, viết câu hỏi, thái độ khi hỏi, đọc câu trả lời, đến cách trả lời câu hỏi cho người khác.
- Ví dụ dở/tốt viết bằng tiếng Anh (React, Postgres…), đúng như thứ bạn sẽ đăng lên cộng đồng quốc tế.
- Mẫu câu hỏi có nút copy.
- Responsive: desktop, tablet, mobile (mục lục tự thu gọn trên mobile).
- Dark mode mặc định, phong cách hacker terminal; thân bài dùng font Be Vietnam Pro cho dễ đọc.

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
- Đề xuất ví dụ thực tế tốt hơn.
- Cải thiện UI/UX/accessibility.
- Dịch sang ngôn ngữ khác (tách branch riêng).

## Bản quyền

- **Bài gốc**: © Eric S. Raymond & Rick Moen — theo [copying policy](http://www.catb.org/~esr/copying.html) tại catb.org.
- **Hướng dẫn tiếng Việt này**: phi lợi nhuận, miễn phí cho mọi mục đích phi thương mại. Đây là bài bình luận dựa trên bản gốc, không phải bản dịch hay phiên bản sửa đổi, đúng với hướng mà copying policy của ESR đề nghị.
- **Mốc thời gian**: dựa trên bài gốc Revision 3.10 (21/05/2014). Viết lần đầu 12/05/2026, cập nhật 02/10/2026.

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
