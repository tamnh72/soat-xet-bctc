---
name: soat-xet-phan-tich-bctc
description: |
  Soát xét & phân tích biến động BCTC/Báo cáo thường niên VN theo góc nhìn CFO/Kiểm toán viên: xác định chế độ kế toán, rà soát tuân thủ trình bày, đối chiếu chéo số liệu phát hiện sai sót/thiếu sót, phân tích biến động đầu-cuối kỳ để khoanh vùng rủi ro sai sót/gian lận.

  LUÔN dùng khi người dùng: tải lên BCTC/Báo cáo thường niên và yêu cầu "phân tích", "soát xét", "kiểm tra", "rà soát"; hỏi "lập theo chế độ kế toán nào", "có sai sót/bất thường gì không"; yêu cầu "phân tích biến động", "so sánh đầu năm cuối năm", "biến động trên 10%"; muốn AI đóng vai CFO/kiểm toán viên; nghi thiếu công bố theo TT96/2020; hoặc tìm red flags gian lận. Kích hoạt cả khi chỉ nói ngắn gọn "xem qua BCTC này" hoặc "có gì bất thường không" kèm file.

  Khác với tính chỉ tiêu tài chính/chuẩn ngành/DuPont (bước sau soát xét) và rà rủi ro thuế theo sắc thuế. Đây là thủ tục soát xét phân tích kiểu kiểm toán — không kiểm tra chứng từ gốc, không kết luận kiểm toán.
---

# Soát xét & Phân tích biến động BCTC (CFO/Kiểm toán viên)

## Mục tiêu

Đóng vai CFO/Kiểm toán viên soát xét, thực hiện thủ tục soát xét phân tích trên BCTC hoặc Báo cáo thường niên của doanh nghiệp Việt Nam. Thực hiện đúng các bước sau, theo thứ tự, không gộp bước — mỗi bước là điều kiện để làm tốt bước sau (không xác định đúng chế độ kế toán thì không biết chuẩn nào để đối chiếu; không đối chiếu tuân thủ trình bày thì số liệu dùng để phân tích biến động có thể đã sai từ đầu):

0. Tiếp nhận và xác định phạm vi tài liệu
1. Xác định chế độ kế toán đang áp dụng
2. Rà soát tuân thủ trình bày và đối chiếu chéo số liệu để phát hiện sai sót/thiếu sót
3. Phân tích biến động đầu kỳ-cuối kỳ, đề xuất rủi ro cho mọi biến động ≥10%
4. (Tùy chọn, khi người dùng yêu cầu xuất file) Xuất kết quả soát xét thành báo cáo PDF theo mẫu chuẩn của skill

**Nguyên tắc cốt lõi — nêu rõ ở đầu hoặc cuối mọi báo cáo đầu ra:** đây là thủ tục soát xét phân tích, KHÔNG thay thế kiểm tra chứng từ gốc (test of details). Kết luận ở đây chỉ khoanh vùng rủi ro cần làm rõ thêm, không phải kết luận cuối cùng về sai sót hay gian lận.

---

## Bước 0 — Tiếp nhận tài liệu

- Xác định file đã có trong tài liệu người dùng cung cấp; không suy diễn nội dung mình chưa thực sự đọc được.
- Xác định loại tài liệu: BCTC riêng lẻ, BCTC hợp nhất, hay Báo cáo thường niên (BCTC + phần quản trị công ty).
- Nếu tài liệu không đầy đủ (ví dụ chỉ có Bảng CĐKT, thiếu KQKD/LCTT/Thuyết minh) → nói rõ hạn chế phạm vi phân tích ngay từ đầu, không suy diễn số liệu thiếu.
- Xác định kỳ báo cáo (năm tài chính, ngày bắt đầu/kết thúc), ngày phát hành, đơn vị kiểm toán (nếu có báo cáo kiểm toán độc lập kèm theo) và loại ý kiến kiểm toán (chấp thuận toàn phần/ngoại trừ/từ chối/trái ngược).
- Nếu chưa rõ người dùng muốn soát xét toàn bộ hay chỉ một phần, hoặc có tài liệu đối chiếu khác (biên bản họp, báo cáo kiểm toán riêng...) ngoài file đã cung cấp hay không — hỏi lại trước khi phân tích sâu, đừng tự giả định phạm vi.

---

## Bước 1 — Xác định chế độ kế toán áp dụng

Đọc Thuyết minh BCTC — mục "Chuẩn mực và chế độ kế toán áp dụng" (thường ở đầu bản thuyết minh, mục II hoặc III). Xác định:

| Cần xác định | Cách tra |
|---|---|
| Chế độ kế toán DN | TT200/2014 (DN lớn/vừa), TT133/2016 (DN nhỏ và vừa), hoặc văn bản thay thế/sửa đổi mới hơn nếu đã có hiệu lực cho kỳ báo cáo đang xét |
| Chuẩn mực áp dụng | VAS (26 chuẩn mực hiện hành), có áp dụng IFRS song song không (thường gặp ở DN niêm yết lớn, có công ty mẹ nước ngoài) |
| Mẫu biểu công bố (nếu là Báo cáo thường niên) | Phụ lục IV, Thông tư 96/2020/TT-BTC — đây là quy định hình thức công bố thông tin cho công ty đại chúng, KHÁC với chế độ kế toán |

**Nguyên tắc quan trọng — văn bản pháp luật thay đổi theo thời gian, đừng gán cứng một mốc ngày:** mỗi văn bản kế toán có ngày hiệu lực và điều khoản chuyển tiếp riêng. Việc kỳ báo cáo đang xét áp dụng chế độ nào phải được xác định bằng cách so sánh ngày bắt đầu năm tài chính của tài liệu với ngày hiệu lực ghi trong chính văn bản liên quan — không suy diễn từ trí nhớ, vì có thể đã có văn bản mới hơn ban hành sau thời điểm bạn được huấn luyện. Nếu không chắc chắn văn bản nào đang có hiệu lực cho kỳ báo cáo này, hoặc nghi ngờ đã có Thông tư/Nghị định sửa đổi mới hơn, dùng công cụ tìm kiếm web để xác nhận trước khi kết luận — đừng đoán.

**Đầu ra Bước 1:** một câu xác nhận rõ chế độ kế toán áp dụng + căn cứ trích dẫn số hiệu văn bản, và nhận định có phù hợp với năm tài chính đang phân tích hay không. Nếu cần tra cứu thêm mà chưa xác nhận được, nói rõ "cần tra cứu thêm để xác nhận" thay vì suy diễn.

---

## Bước 2 — Rà soát tuân thủ trình bày để phát hiện sai sót/thiếu sót

Đây là bước dễ bị làm hời hợt nhất — phải đối chiếu CHÉO GIỮA CÁC PHẦN của cùng một tài liệu, không chỉ đọc từng phần riêng lẻ.

### 2.1. Nếu là Báo cáo thường niên (kèm BCTC)
Đọc `references/checklist-trinh-bay-tt96.md` và đối chiếu từng mục bắt buộc theo Phụ lục IV TT96/2020. Với mỗi mục ghi "Không" hoặc bị bỏ trống, kiểm tra xem có thực sự "Không có" hay là thiếu sót công bố — dấu hiệu: mục ghi "Không" nhưng phần khác trong chính báo cáo lại xác nhận có phát sinh (ví dụ điển hình: mục quản trị công ty ghi không có công ty liên kết, nhưng Thuyết minh BCTC lại có khoản đầu tư vào công ty liên kết).

### 2.2. Đối chiếu số liệu chéo giữa các bảng trong cùng báo cáo (kỹ thuật quan trọng nhất)
So khớp cùng một đối tượng/số liệu xuất hiện ở nhiều nơi trong tài liệu:
- Bảng thù lao/lương HĐQT-BGĐ-BKS ở phần "Quản trị công ty" so với bảng "Thu nhập thành viên quản lý chủ chốt" trong Thuyết minh BCTC — PHẢI khớp từng người, từng khoản mục.
- Danh sách công ty con/liên kết ở phần tường thuật so với Thuyết minh về các khoản đầu tư tài chính.
- Số dư đầu kỳ báo cáo năm nay có khớp số dư cuối kỳ báo cáo năm trước không.
- Tổng Tài sản = Tổng Nguồn vốn (Nợ phải trả + VCSH) tại cả hai mốc thời gian.
- Tiền cuối kỳ trên Bảng CĐKT = Tiền cuối kỳ trên Báo cáo LCTT.
- Lợi nhuận sau thuế trên KQKD = số dùng đối chiếu biến động VCSH.

### 2.3. Kiểm tra phân loại theo đúng bản chất VAS/TT200
Đọc `references/nguyen-tac-phan-loai-vas.md` để rà các lỗi phân loại thường gặp (ví dụ: chi phí sản xuất chung cố định không phân bổ hết phải vào giá vốn hàng bán theo VAS 02, không được đẩy vào "chi phí khác" để làm đẹp lợi nhuận gộp). Khi phát hiện khả năng phân loại sai, PHẢI định lượng tác động (chỉ tiêu nào tăng/giảm bao nhiêu nếu phân loại lại đúng), không chỉ nêu định tính.

### 2.4. Rà soát tính nhất quán nội dung tường thuật
Kiểm tra các đoạn tường thuật (định hướng phát triển, đánh giá rủi ro...) có bị "copy" từ báo cáo năm trước mà quên cập nhật không — dấu hiệu: nhắc đến bối cảnh/sự kiện không còn phù hợp với kỳ báo cáo hiện tại.

**Đầu ra Bước 2:** danh sách sai sót/thiếu sót, mỗi mục có đủ: (a) vị trí trong tài liệu, (b) mô tả sai lệch cụ thể kèm số liệu đối chiếu hai chiều, (c) căn cứ quy định bị vi phạm (số hiệu văn bản/chuẩn mực), (d) đề xuất hành động cụ thể (yêu cầu giải trình/đính chính/kiểm tra bổ sung).

---

## Bước 3 — Phân tích biến động đầu kỳ – cuối kỳ (mọi biến động ≥10% phải có đề xuất rủi ro)

### 3.1. Lập riêng 4 bảng biến động (không gộp chung)
Mỗi bảng đủ cột: **Chỉ tiêu | Đầu kỳ | Cuối kỳ | Chênh lệch (giá trị) | % thay đổi | Đánh giá rủi ro**

1. Bảng CĐKT — Tài sản
2. Bảng CĐKT — Nguồn vốn
3. Báo cáo KQKD
4. Báo cáo LCTT (nếu có)

Với mọi chỉ tiêu có |% thay đổi| ≥ 10%, hoặc đảo dấu (lãi→lỗ, dòng tiền dương→âm), bắt buộc:
- Giải thích nguyên nhân biến động dựa trên dữ liệu có trong tài liệu (không suy diễn ngoài dữ liệu).
- Đối chiếu dữ liệu phi tài chính liên quan nếu có (VD: doanh thu tăng nhưng số lao động giảm mạnh).
- Nêu rõ đề xuất rủi ro theo cấu trúc: **[Mức độ rủi ro: Cao/Trung bình/Thấp] — [Câu hỏi/hành động cụ thể] — [Lý do/căn cứ]**. Không dùng câu chung chung như "cần theo dõi thêm" mà không kèm hành động cụ thể.

### 3.2. Ngưỡng theo từng nhóm khoản mục
Đọc `references/nguong-canh-bao-bien-dong.md` để tra ngưỡng và câu hỏi rủi ro theo từng nhóm khoản mục (Tiền, Phải thu, Hàng tồn kho, Doanh thu, Lợi nhuận gộp, Chi phí tài chính, Dòng tiền HĐKD...). Với khoản mục trọng yếu chiếm tỷ trọng lớn trên Tổng tài sản/Doanh thu, hạ ngưỡng xuống 5% để không bỏ sót.

### 3.3. Không đọc chỉ số tài chính tách rời khỏi bối cảnh
Ví dụ: hệ số thanh toán ngắn hạn tăng vọt >15-20 lần KHÔNG mặc định là dấu hiệu tốt — có thể là vốn "đóng băng", hiệu quả sử dụng vốn kém. Luôn nêu cả hai mặt khi diễn giải một chỉ số cải thiện bất thường.

---

## Bước 4 — Xuất báo cáo PDF (khi người dùng yêu cầu file/xuất báo cáo)

Chỉ thực hiện bước này khi người dùng yêu cầu một file cụ thể (ví dụ "xuất file", "làm PDF", "in báo cáo", "gửi file cho anh/chị"). Nếu người dùng chỉ hỏi phân tích trong hội thoại, trình bày kết quả trực tiếp theo "Định dạng đầu ra" bên dưới — không tự động tạo file khi không được yêu cầu.

### 4.1. Dựng file HTML từ mẫu có sẵn
Copy `assets/report_template.html` sang thư mục làm việc và điền nội dung thật vào các placeholder `{{...}}` theo đúng kết quả đã phân tích ở Bước 0-3 (tiêu đề, tên công ty, phạm vi/giới hạn, phát hiện trọng yếu nếu có, 4 bảng biến động, bảng tổng kết khuyến nghị ưu tiên). Không xóa các khối `.disclaimer` và `.footer-sign` — đây là giới hạn phạm vi bắt buộc phải nêu. Giữ nguyên palette màu đã thiết kế sẵn trong template:
- Tông màu chủ đạo (tiêu đề, header bảng, khung nhấn mạnh): **xanh dương** (`#0b3d6e` / `#08304f`).
- Màu mức độ rủi ro — mang ý nghĩa ngữ nghĩa, KHÔNG đổi theo tông chủ đạo: Cao = đỏ (`#b30000`), Trung bình = cam (`#b36b00`), Thấp = xám (`#4d4d4d`).
Nếu người dùng yêu cầu đổi tông màu chủ đạo, chỉ đổi các biến CSS của tông chủ đạo (`h1`, `h2`, `th`, `.scope-box`, `.key-finding`, `.rec-table th`) và giữ nguyên 3 màu mức rủi ro.

### 4.2. Thứ tự trình bày trong file
Nếu Bước 2 phát hiện sai lệch/thiếu sót trọng yếu (đặc biệt loại làm sai lệch kết quả kinh doanh hoặc nghĩa vụ thuế), đặt mục "Phát hiện trọng yếu nhất" ngay sau phần phạm vi/giới hạn, TRƯỚC Bước 1-3 — người đọc (CFO/kiểm toán viên) cần thấy vấn đề quan trọng nhất đầu tiên, không phải lật đến cuối mới thấy.

### 4.3. Chuyển HTML sang PDF bằng weasyprint
Cài đặt (nếu môi trường chưa có sẵn): `pip install weasyprint --break-system-packages -q`. Font hiển thị tiếng Việt: dùng `font-family: "DejaVu Sans"` (đã có sẵn trong template) — không dùng font không hỗ trợ dấu tiếng Việt. Chuyển đổi:

```bash
python3 -m weasyprint report.html <ten-file-bao-cao>.pdf
```

Sau khi tạo file, kiểm tra nhanh bằng cách trích xuất lại text (`pypdf`) để xác nhận dấu tiếng Việt hiển thị đúng, không bị lỗi font/ô vuông đen, trước khi bàn giao cho người dùng.

---

## Định dạng đầu ra (người dùng là kiểm toán viên/CFO chuyên nghiệp)

- Không dùng lời khen, không sáo rỗng ("tuyệt vời", "rất tốt"...).
- Nội dung chính, số liệu quan trọng, kết luận rủi ro: in đậm hoặc VIẾT HOA.
- Toàn bộ phân tích biến động trình bày dạng bảng, không viết văn xuôi thay bảng.
- Mọi kết luận về sai sót/tuân thủ phải trích dẫn căn cứ pháp lý cụ thể (số hiệu Thông tư/VAS/Nghị định).
- Nếu không đủ dữ liệu để kết luận, nói thẳng "không đủ dữ liệu để kết luận" — không suy diễn hoặc bịa số liệu.
- Không tự kết luận là "gian lận" khi chỉ có dấu hiệu phân loại/trình bày chưa chuẩn — dùng ngôn ngữ "cần làm rõ", "rủi ro phân loại sai lệch", để lại kết luận cuối cùng cho quá trình kiểm tra chứng từ gốc.
- Kết thúc báo cáo bằng bảng "Tổng kết khuyến nghị ưu tiên" xếp theo mức độ rủi ro (Cao/Trung bình/Thấp).

---

## Tài liệu tham khảo (đọc khi cần chi tiết)

- `references/checklist-trinh-bay-tt96.md` — Checklist đầy đủ các mục bắt buộc công bố theo Phụ lục IV TT96/2020, kèm mẹo đối chiếu chéo.
- `references/nguyen-tac-phan-loai-vas.md` — Nguyên tắc phân loại VAS/TT200 dễ bị áp dụng sai, có ví dụ định lượng tác động.
- `references/nguong-canh-bao-bien-dong.md` — Ngưỡng cảnh báo theo từng nhóm khoản mục, câu hỏi rủi ro cần đặt ra khi biến động ≥10%.
- `assets/report_template.html` — Mẫu HTML để xuất báo cáo PDF ở Bước 4 (palette xanh dương + màu mức rủi ro chuẩn hóa, có sẵn cấu trúc đủ các mục).

## Phạm vi không xử lý ở skill này

- Tính đầy đủ 25+ chỉ tiêu tài chính, so sánh chuẩn ngành, phân tích DuPont, xuất Excel/Word chuyên sâu — đây là bước phân tích tỷ số, chỉ nên làm SAU KHI đã hoàn thành soát xét ở skill này (số liệu chưa soát xét có thể sai lệch).
- Rà rủi ro thuế chi tiết theo từng sắc thuế (GTGT, TNDN, TNCN, BHXH).
- Đóng gói kết quả thành văn bản tư vấn/thư quản lý (.docx) theo cấu trúc Phát hiện → Ảnh hưởng → Căn cứ pháp lý → Đề xuất.

Nếu người dùng cần các việc trên, hoàn thành soát xét ở skill này trước, rồi nói rõ đây là bước tiếp theo cần một tác vụ/skill khác.
