# NHẬT KÝ THỰC HIỆN LAB 6 (LOGBOOK)

* **Họ và tên: Lại Nguyễn Hữu Nhân** 
* **Mã sinh viên: PS51442** 
* **Link Repository cá nhân:** 

> [!NOTE]
> **HƯỚNG DẪN DÀNH CHO KỶ NGUYÊN AI:**  
> Bạn được khuyến khích sử dụng AI (Cursor, Copilot, ChatGPT, Claude) như một trợ lý lập trình. Tuy nhiên, AI thường xuyên sinh mã lỗi đối với các trường hợp biên (biên mảng, số âm, tràn chỉ số). Hãy ghi lại trung thực quá trình bạn phát hiện và khắc phục lỗi của AI.

---

### Lần 1: Bài 1 - Bộ Lọc Làm Mịn Tín Hiệu (Moving Average)
- Trạng thái: Chờ chấm
- Prompt hỏi AI (nếu có): đã dùng AI để tham khảo cách trình bày
- Lỗi phát hiện qua Test (nếu có): chưa có
- Cách sửa / Bài học: Chờ kết quả phản hồi từ GitHub Actions

### Lần 2: Bài 1
- Trạng thái: sửa lỗi lần 2
- Lỗi / Cách sửa: Hoán đổi vị trí xử lý giữa phần tử ở giữa mảng (else if) và phần tử biên cuối (else).

### Lần 3: Bài 1 (Dự phòng)
- Trạng thái: 
- Lỗi / Cách sửa: 

---

### Lần 4: Bài 2 - Nén Sai Phân Dữ Liệu IoT (Delta Encoding)
- Trạng thái: Chờ chấm
- Prompt hỏi AI (nếu có): đã dùng AI , hỏi AI cách trình bày
- Lỗi phát hiện qua Test (nếu có): chưa có
- Cách sửa / Bài học: Chờ kết quả phản hồi từ GitHub Actions
+

### Lần 5: Bài 2
- Trạng thái: 
- Lỗi / Cách sửa: 

### Lần 6: Bài 2 (Dự phòng)
- Trạng thái: 
- Lỗi / Cách sửa: 

---

### Lần 7: Bài 3 - Bộ Lọc Làm Mờ Điểm Ảnh (Box Blur Filter 3x3)
- Trạng thái: chờ chấm
- Prompt hỏi AI (nếu có): đoạn code lamMoMaTran của tôi đang tính ra kết quả bị sai số ở các ô nằm ở biên và góc của ma trận, đồng thời các ô phía sau bị lệch giá trị,  code bị lỗi ở bên dưới, chỉ ra những dòng nào bị sai, giải thích ngắn gọn nguyên nhân: int tong = 0; 
    int dem = 0; 
    for (int i = 0; i < row; i++){
        for (int j = 0; j < col; j++){
            for (int r = i - 1; r <= i + 1; r++){
                for (int c = j - 1; c <= j + 1; c++){
                    if (r >= 0 && r < row && c >= 0 && c < col){
                        tong += src[r][c];
                        dem++;
                    }
                }
            }
            dest[i][j] = tong / 9; 
        }
    }
- Lỗi phát hiện qua Test (nếu có): Lỗi chia cố định cho 9 thay vì chia cho số lượng ô lân cận
- Cách sửa / Bài học: Chờ kết quả phản hồi từ GitHub Actions

### Lần 8: Bài 3
- Trạng thái: 
- Lỗi / Cách sửa: 

### Lần 9: Bài 3 (Dự phòng)
- Trạng thái: 
- Lỗi / Cách sửa: 

---

### Lần 10: Bài 4 - Radar Dò Điểm Nóng (Thermal Peak Detection)
- Trạng thái: 
- Prompt hỏi AI (nếu có): 
- Lỗi phát hiện qua Test (nếu có): 
- Cách sửa / Bài học: 

### Lần 11: Bài 4
- Trạng thái: 
- Lỗi / Cách sửa: 

### Lần 12: Bài 4
- Trạng thái: 
- Lỗi / Cách sửa: 

### Lần 13: Bài 4 (Dự phòng)
- Trạng thái: 
- Lỗi / Cách sửa: 
