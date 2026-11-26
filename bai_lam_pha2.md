# BÀI LÀM PHA 2 – HACKATHON 02

- **Mã đề:** 06
- **Họ tên:**Cao Bảo Lâm
- **Lớp:**CNTT2
- **Link repository Pha2:**https://github.com/Baolam070108/-HN-KS26--CNTT2_Pha1.git
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):**chatgpt

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt bàn ra JSON

**KET QUA AI**

```text
[
  {
    "ma_buffet": "NUONG",
    "ngay_dat": "2026-12-19",
    "nguoi_lon": 2,
    "tre_em": 1,
    "khu_vuc": "trong_nha",
    "ghi_chu": null
  },
  {
    "ma_buffet": "HAISAN",
    "ngay_dat": "2027-01-03",
    "nguoi_lon": 3,
    "tre_em": 0,
    "khu_vuc": null,
    "ghi_chu": "1 người dị ứng sữa"
  },
  {
    "ma_buffet": "LAU",
    "ngay_dat": "2026-12-25",
    "nguoi_lon": 4,
    "tre_em": 0,
    "khu_vuc": "san_vuon",
    "ghi_chu": "Ông ngoại đi xe lăn"
  }
]
```

**Link trò chuyện:** https://chatgpt.com/share/6b079ddb-1c68-83ec-9517-2937bf3ca45c

## 4.3. Báo giá bằng Chain-of-Thought

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**

### b) Kiểm tra kết quả AI

(Ghi kết luận AI đúng hay sai; nếu sai, ghi bước sai đầu tiên và kết quả đúng của bước đó – xoá dòng này)

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "thieu_mon",
  "so_khach": 5,
  "so_mon_bi_thieu": 2,
  "tom_tat": "Nhà hàng quảng cáo có tôm hùm và cua nhưng cả buổi tối hai món đều hết, khách đã chờ 2 lần bổ sung nhưng vẫn không có."
}
```

**Link trò chuyện:**https://chatgpt.com/share/6b079ef5-6218-83ec-b5ee-08e59bb668e5

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
| Tiêu chí | Điểm | Minh chứng | Đề xuất sửa |
|---|---:|---|---|
| Đúng thông tin (50%) | 0/5 | **Lỗi:** Không có câu trả lời của nhân viên để đối chiếu. Nội dung được cung cấp chỉ là câu hỏi của khách hàng. Chưa xác nhận được giá buffet lẩu 299.000 đồng/người lớn và quy định trễ 40 phút sẽ bị huỷ bàn. | "Buffet lẩu có giá 299.000 đồng/người lớn. Theo quy định, nếu quý khách đến trễ trên 30 phút, nhà hàng sẽ huỷ bàn đã đặt." |
| Đầy đủ (30%) | 0/3 | **Lỗi:** Chưa có câu trả lời cho hai câu hỏi của khách và chưa có lời mời khách cung cấp ngày, giờ đến, số lượng khách để đặt bàn. | "Quý khách vui lòng cung cấp ngày đến, giờ đến và số lượng khách để nhà hàng hỗ trợ đặt bàn ạ." |
| Giọng điệu (20%) | 0/2 | **Lỗi:** Chưa có nội dung tư vấn của nhân viên nên chưa thể đánh giá mức độ lịch sự và chuyên nghiệp. | Sử dụng cách xưng hô "quý khách", "nhà hàng" và lời văn lịch sự, chuyên nghiệp. |
| **Tổng điểm** | **0/10** | **Chưa cung cấp câu trả lời của nhân viên để chấm điểm. Nội dung hiện tại chỉ là đề bài và câu hỏi của khách hàng.** | **Cần bổ sung câu trả lời của nhân viên để đánh giá chính xác.** |
```

**Link trò chuyện:**https://chatgpt.com/share/6b079f7a-1574-83ec-a655-5f7ffdd068f8
