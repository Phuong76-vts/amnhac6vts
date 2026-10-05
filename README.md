# Phòng thu nhịp C

Học liệu số **Âm nhạc 6** – Chủ đề 3 *Nhớ ơn thầy cô*, Nhạc lí: **Nhịp 4/4** (SGK Kết nối tri thức với cuộc sống)
Tác giả: Lê Thị Hà – giáo viên Âm nhạc, Tổ Khoa học xã hội
Trường THCS Võ Thị Sáu, Hải Phòng – Năm học 2026 – 2027

## Ý tưởng

Một "phòng thu" trên bảng xanh phòng nhạc: học sinh nghe phách mạnh – nhẹ – mạnh vừa – nhẹ, tập kẻ vạch nhịp, chơi trò gõ theo phách, rồi tự sáng tác 4 ô nhịp tiết tấu ở nhịp C để tặng thầy cô. Âm thanh tạo trực tiếp bằng Web Audio (không cần tệp âm thanh).

## 6 nhiệm vụ

| Bước | Nhiệm vụ |
|---|---|
| Khám phá | (1) Nghe "nhịp tim" của bản nhạc: so sánh 2/4, 3/4, 4/4, sơ đồ đánh nhịp có chấm sáng chạy theo phách; đoán nhịp 3 đoạn bí ẩn. (2) Trường độ (tròn, trắng, đen, móc đơn, lặng đen), biến hình 4/4 ⇄ C, đếm phách trong 6 ô nhịp |
| Luyện tập | (3) Kẻ vạch nhịp cho 2 dòng tiết tấu. (4) Gõ theo phách: nút MẠNH (phím F) / NHẸ (phím J), chấm độ chính xác, cần từ 70% |
| Sáng tạo | (5) Phòng thu: đặt mẫu tiết tấu vào 4 ô nhịp, chọn nhạc cụ (trống, song loan, thanh phách, trống lắc), tốc độ, phát lại; tạo thẻ "Bản tiết tấu tặng thầy cô" |
| Thử thách | (6) 6 câu trắc nghiệm có gợi ý |

## Bản quyền

Tiết tấu do giáo viên tự soạn; không sao chép bài hát, bài đọc nhạc, hình ảnh của SGK. Kí hiệu nốt nhạc vẽ bằng mã nguồn (SVG), âm thanh tạo bằng Web Audio. Mã nguồn có sử dụng công cụ AI hỗ trợ lập trình; nội dung đã được giáo viên kiểm tra. App không thu thập dữ liệu; tiến độ chỉ lưu trên máy học sinh.

## Đưa lên GitHub và Vercel

1. github.com → **New repository** → tên `phong-thu-nhip-c` → tải lên `index.html`, `README.md`.
2. vercel.com → **Add New… → Project** → chọn repo → **Deploy**.

## Sửa nhanh

- Màu: khối `:root` đầu file. Âm thanh nhạc cụ: hàm `hit()`; tiếng đếm phách: `click()`.
- Ô nhịp đếm phách: `B6`. Dòng kẻ vạch nhịp: `VN`. Gợi ý ngẫu nhiên: `RAND`. Câu hỏi: `QZ`.
