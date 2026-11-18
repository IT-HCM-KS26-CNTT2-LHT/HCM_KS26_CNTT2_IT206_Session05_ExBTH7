# [Bài thực hành 7] Xây dựng kế hoạch tổ chức sự kiện công nghệ AI Innovation Day

## 1. Bộ prompt (kết quả bước trước dán vào bước sau)

| Bước | Kỹ thuật | Prompt |
|---|---|---|
| P0 | Context Management | "AI Innovation Day: 1 ngày, 150 SV, 10 nhân sự, tối đa 15 triệu. Không đổi các ràng buộc này." |
| P1 | Chain-of-Thought | "Phân tích khả thi **từng bước**: nhân sự, ngân sách, thời gian, rủi ro, kết luận." |
| P2 | Prompt Chaining | "Dựa trên P1, lập lịch trình theo giờ." |
| P3 | CoT + Chaining | "Dựa trên P2, lập dự toán **từng bước**, tổng tối đa 15 triệu, có dự phòng." |
| P4 | Prompt Chaining | "Dựa trên P2, P3, phân công 10 người." |
| P5 | Prompt Chaining | "Dựa trên P2 đến P4, lập kế hoạch truyền thông." |
| P6 | Chain-of-Thought | "Kiểm tra **từng bước** P1 đến P5, tìm mâu thuẫn." |
| P7 | Prompt Chaining | "Sửa lỗi ở P6, xuất bản cuối." |
| P8 | Context Management | "Tóm tắt dự án tối đa 300 từ để dùng ở hội thoại mới." |

## 2. Phân tích khả thi

- **Nhân sự:** 10 người / 150 SV, đủ nếu chia vai rõ.
- **Ngân sách:** khoảng 100.000đ/SV, không bao ăn trưa (SV tự túc).
- **Thời gian:** 1 ngày đủ cho 2 talk, 1 workshop, 1 hackathon.
- **Rủi ro:** wifi yếu (có 4G dự phòng), diễn giả hủy (có người dự bị), thiếu đăng ký (có danh sách chờ).
- **Kết luận: khả thi.**

## 3. Lịch trình

| Giờ | Nội dung |
|---|---|
| 07:30-08:30 | Check-in |
| 08:30-09:00 | Khai mạc |
| 09:00-10:00 | Talk 1: AI trong học tập |
| 10:00-10:15 | Tea break |
| 10:15-11:30 | Workshop prompt |
| 11:30-13:00 | Nghỉ trưa |
| 13:00-14:00 | Talk 2: AI trong công việc |
| 14:00-15:30 | Mini-hackathon |
| 15:30-15:45 | Tea break |
| 15:45-16:30 | Demo, trao giải, bế mạc |

## 4. Dự toán ngân sách

| Hạng mục | Tiền (đ) |
|---|---|
| Âm thanh, máy chiếu | 1.500.000 |
| Diễn giả (2 người) | 2.000.000 |
| Tea break (165 người x 2 x 15.000) | 4.950.000 |
| In ấn | 1.500.000 |
| Giải thưởng | 2.500.000 |
| Áo BTC, văn phòng phẩm | 800.000 |
| Truyền thông | 700.000 |
| Dự phòng | 1.050.000 |
| **Tổng** | **15.000.000** |

## 5. Phân công 10 nhân sự

1. Trưởng ban
2. MC
3. Nội dung, diễn giả
4. Kỹ thuật
5. Tài chính
6. Hậu cần
7. Truyền thông, thiết kế
8. Truyền thông, đăng ký
9. Check-in
10. Cuộc thi, giải thưởng

## 6. Truyền thông

| Mốc | Hoạt động | Phụ trách |
|---|---|---|
| T-21 | Teaser, công bố sự kiện | #7, #8 |
| T-18 | Mở form đăng ký | #8 |
| T-14 | Giới thiệu diễn giả | #3, #7 |
| T-10 | Dán poster, nhờ chia sẻ | #7, #9 |
| T-5 | Nhắc lịch, "tự túc ăn trưa" | #8 |
| T-1 | Nhắc lần cuối | #8 |

## 7. Tóm tắt ngữ cảnh

> AI Innovation Day, 1 ngày. **Cố định:** 150 SV, 10 nhân sự, tối đa 15 triệu. **Đã chốt:** 2 talk, 1 workshop, 1 hackathon, 2 tea break; SV tự túc ăn trưa. **Ngân sách:** 8 mục, tổng 15 triệu, dự phòng 1,05 triệu. **Đã sửa:** giải thưởng từ 3,2 xuống 2,5 triệu. **Còn lại:** kịch bản MC, checklist.

## 8. Kiểm tra và hiệu chỉnh

| Kiểm tra | Kết quả |
|---|---|
| Ngân sách tối đa 15 triệu | Đạt |
| Giữ 150 SV, 10 nhân sự | Đạt |
| Các hạng mục khớp nhau | Đạt |

**Lỗi đã sửa:**

1. Giải thưởng quá cao, dự phòng chỉ khoảng 2%. Giảm giải thưởng còn 2,5 triệu.
2. Có nghỉ trưa nhưng không có tiền ăn. Ghi rõ "SV tự túc".
3. Hackathon thiếu giám khảo. Dùng 2 diễn giả làm giám khảo.

**Kết luận:** kế hoạch khả thi, không vượt ngân sách, các hạng mục thống nhất.
