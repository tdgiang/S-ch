# Sống Đáng Giá

Bản dịch tiếng Việt của «高性价比人生指南» (HowToLiveBetter), đọc trên web tại GitHub Pages.

## Nguồn và giấy phép

- Bản gốc: «高性价比人生指南» – https://github.com/eternity4719/HowToLiveBetter
- Dịch theo phiên bản commit `e2605d3e2242bd6216c9255192b8a8957a08c55a` (21/10/2026).
- Nội dung gốc phát hành theo [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Bản dịch này cũng phát hành theo CC BY 4.0.
- Thay đổi so với bản gốc: dịch sang tiếng Việt, bỏ link "về mục lục" đầu chương, thêm ghi chú phạm vi áp dụng (luật và chính sách theo Trung Quốc).

## Cấu trúc

- `index.html` – toàn bộ web (mục lục và trang đọc chương).
- `chapters.json` – danh sách 34 chương, `done: true` là chương đã dịch.
- `chapters/NN.md` – nội dung chương đã dịch.

## Thêm chương mới

1. Dịch `book/NN-*.md` của bản gốc, lưu vào `chapters/NN.md`.
2. Trong `chapters.json`, đổi `done` của chương đó thành `true`.
3. Commit và push. GitHub Pages tự cập nhật sau khoảng 1 phút.

## Chạy thử trên máy

```sh
python3 -m http.server 8000
# mở http://localhost:8000
```
