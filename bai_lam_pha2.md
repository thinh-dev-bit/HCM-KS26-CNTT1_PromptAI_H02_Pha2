# BÀI LÀM PHA 2 

- **Họ tên:** Trịnh Phú Thịnh
- **Lớp:** HCM-KS26-CNTT1
- **Link repository Pha2:**
- **Công cụ AI đã dùng (ChatGPT/Claude/Gemini):** Claude

> Pha 2 (20 phút cuối). Mỗi mục: mở cuộc trò chuyện mới, gửi nguyên văn prompt đã viết trong bai_lam_pha1.md, dán câu trả lời và link chia sẻ vào đây. Xong, kéo thả file này vào repository Pha2.

## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[
{"ma_goi": "SVT", "ngay_su_kien": "2026-12-20", "nguoi_lon": 2, "tre_em": 1, "loai_ve": "thuong", "ghi_chu": null},
{"ma_goi": "FZ", "ngay_su_kien": "2027-01-05", "nguoi_lon": 3, "tre_em": 0, "loai_ve": null, "ghi_chu": "một người cần hỗ trợ xe lăn"},
{"ma_goi": "VIP", "ngay_su_kien": null, "nguoi_lon": 4, "tre_em": 0, "loai_ve": "vip", "ghi_chu": "một người khiếm thị cần hỗ trợ tìm chỗ"}
]
```

**Link trò chuyện:**https://claude.ai/share/58379ee9-886b-49d7-99d0-95ad3b52667b

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
Kính chào Quý khán giả,

Ban tổ chức giải bóng đá Cúp Sao Vàng xin gửi báo giá vé trận bán kết cho nhóm của Quý khán giả (gói SVT – Sân Vận Động, đơn giá người lớn 1.200.000 đồng):

Bước 1 – Tiền người lớn
5 người lớn × 1.200.000 = 6.000.000 đồng

Bước 2 – Tiền trẻ em

Trẻ 8 tuổi và 10 tuổi thuộc nhóm 5–11 tuổi, tính 70% giá người lớn: 1.200.000 × 70% = 840.000 đồng/trẻ
2 trẻ × 840.000 = 1.680.000 đồng
Bé 3 tuổi (dưới 5 tuổi): miễn phí = 0 đồng

Bước 3 – Tiền vé (trước giảm giá)
6.000.000 + 1.680.000 + 0 = 7.680.000 đồng

Bước 4 – Giảm giá nhóm
Nhóm có 5 người lớn, đủ điều kiện giảm 5% trên tiền vé:

Số tiền giảm: 7.680.000 × 5% = 384.000 đồng
Tiền vé sau giảm: 7.680.000 − 384.000 = 7.296.000 đồng

Bước 5 – Phụ thu khu ghế ưu tiên
1 người × 300.000 = 300.000 đồng (phụ thu không được giảm giá)

Bước 6 – Tổng tiền
7.296.000 + 300.000 = 7.596.000 đồng

Trân trọng cảm ơn Quý khán giả đã quan tâm và đồng hành cùng giải đấu. Ban tổ chức rất mong được đón tiếp nhóm tại sân vận động.

[RESULT: 7596000 đồng]
```

**Link trò chuyện:**https://claude.ai/share/0d24fca4-1a9b-480e-91be-920c1576a62e

### b) Kiểm tra kết quả AI

Kết quả AI: Đúng
## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{"loai_su_co": "sai_khu_vuc", "so_khach": 2, "so_hiep_bi_anh_huong": 2, "tom_tat": "Khách gói SVT cam kết có mái che nhưng bị xếp khu không mái suốt hai hiệp đầu."}
```

**Link trò chuyện:**https://claude.ai/share/422340d4-8030-492e-bfcb-e8f2946d082c

## 4.5. Prompt chấm bài theo Rubric

**KET QUA AI**

```text
(Dán câu trả lời của AI vào đây (bấm nút Copy dưới câu trả lời) – xoá dòng này)
```

**Link trò chuyện:**
