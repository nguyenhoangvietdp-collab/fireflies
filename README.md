# Fireflies – Những đốm lửa biết bay

Kho lưu toàn bộ dữ liệu dự án truyền thông **"Một đêm đúng nghĩa"** của đội **Những đốm lửa biết bay**, dự thi **WATT'S UP** (chiến dịch 4 tuần, 02/11–29/11/2026).

Repo này là **bản sao lưu để làm việc offline / trên máy local**. Bản "sống" (đang được cả đội sửa) vẫn là các file Google Docs / Google Sheets ở mục [Link gốc](#link-gốc-bản-đang-dùng). Ngày chụp dữ liệu: **02/11/2026**.

> ⚠️ Thể lệ WATT'S UP (điều D1) cấm dùng AI để sản xuất nội dung chiến dịch. Mọi bản thảo trong repo chỉ là **tài liệu tham khảo, định hướng**; đội phải tự viết lại và chịu trách nhiệm nội dung trước khi gửi BTC duyệt.

---

## Cấu trúc thư mục

```
fireflies/
├── README.md                         ← file bạn đang đọc
├── skills/                           ← 2 skill viết content cho Claude
│   ├── copywriting-vi-en/SKILL.md
│   └── wattsup-copywriting/SKILL.md
├── tai-lieu/                         ← các tài liệu chính (bản .md để đọc nhanh, .docx để mở bằng Word)
│   ├── 01-cam-nang-marketing-storytelling.md / .docx
│   ├── 02-ban-thao-content-tuan-1.md / .docx
│   ├── 03-gop-y-kich-ban-phim.md
│   └── 04-tong-hop-gop-y-chuyen-gia.md / .docx
└── tracking/                         ← trang tính theo dõi tiến độ
    ├── Tracking-file-Google-Sheet.xlsx        (bản mới nhất, xuất từ Google Sheet chính)
    ├── ban-cu-Watts-up-Tracking-file-da-dien.xlsx (bản .xlsx cũ, giữ để đối chiếu)
    └── csv/                                   (từng tab của Google Sheet, dạng CSV)
        ├── 01-tong-quan.csv
        ├── 02-master-checklist.csv
        ├── 03-timeline.csv
        ├── 04-cac-dau-moi-quan-trong.csv
        └── 05-kol-koc-dau-moi.csv
```

---

## Từng file dùng để làm gì

### `skills/` – bộ hướng dẫn viết content cho Claude

| File | Dùng khi nào |
|---|---|
| `skills/copywriting-vi-en/SKILL.md` | Skill **dùng chung cho mọi dự án**: viết, sửa, rà soát, chuyển ngữ copywriting tiếng Việt và tiếng Anh cho mạng xã hội, chiến dịch, quảng cáo. |
| `skills/wattsup-copywriting/SKILL.md` | Skill **riêng cho chiến dịch "Một đêm đúng nghĩa"**: đã gắn sẵn bối cảnh WATT'S UP, giọng văn, quy định kênh FB/IG/TikTok/Threads/YouTube, hashtag, logo, miễn trừ EU. |

Cách cài đặt xem ở mục [Dùng các skill](#dùng-các-skill-với-claude).

### `tai-lieu/` – tài liệu chính

| File | Nội dung | Khi nào mở |
|---|---|---|
| `01-cam-nang-marketing-storytelling` | **Cẩm nang nền tảng.** Phần 0: tổng hợp thể lệ WATT'S UP (mốc thời gian, cách chấm 100 điểm, quy định truyền thông, câu hỏi còn mở cho BTC). Phần 1–8: Kotler (STP, 4P/7P/4C, 5A), IMC & PESO, công thức copywriting (AIDA, PAS, BAB, 4U…), khung storytelling, văn hoá viết và ấn phẩm Việt Nam, điều cần tránh (Luật Quảng cáo 2025), checklist trước khi đăng. **Tab thứ 2 "Chiến dịch IMC" (v1.3)**: kênh chính/phụ, so sánh FB vs IG, PESO, 8 nhóm nội dung, Bảo tàng bóng đêm, KOL/KOC, lộ trình 4 tuần, 4 lô duyệt EU, định hướng Threads, ngân sách 6 triệu, câu hỏi còn mở. | Trước khi lên ý tưởng / viết bất kỳ bài nào; khi cần tra quy định cuộc thi. |
| `02-ban-thao-content-tuan-1` | **Bản thảo content tuần 1 (02/11–08/11)**: 43 bài, chia tab theo kênh (Tổng quan, Facebook 19, Instagram 19, TikTok 3, Threads 2). Mỗi bài có ngày giờ đăng, lô duyệt (1A/1B), đề xuất hình ảnh, kịch bản video, caption, hashtag, miễn trừ EU. Bản .docx giữ đúng định dạng "mỗi bài một trang, dạng bảng". | Khi sản xuất / gửi duyệt bài tuần 1. |
| `03-gop-y-kich-ban-phim` | Góp ý kịch bản phim ngắn **"Nuốt lấy ánh sáng"**: kết luận chung, góp ý theo cảnh, nhịp phim, lỗi thời lượng, checklist tuân thủ BTC trước khi quay. | Khi chỉnh kịch bản / trước khi quay. |
| `04-tong-hop-gop-y-chuyen-gia` | Tổng hợp góp ý của chuyên gia đồng hành (Technical Mentor, Communication Module) và **28 câu hỏi cần duyệt** chia 5 nhóm A–E, có mức ưu tiên và nên hỏi ai. | Khi soạn email/tin nhắn hỏi BTC, mentor. |

> File `.md` là bản xuất tự động từ Google Docs nên bảng và định dạng có thể đơn giản hơn bản gốc. Nếu cần đúng bố cục, mở file `.docx` hoặc link Google Docs gốc.

### `tracking/` – trang tính theo dõi

| File | Nội dung |
|---|---|
| `Tracking-file-Google-Sheet.xlsx` | Bản xuất đầy đủ của trang tính chính (giữ công thức, định dạng, menu chọn). Mở bằng Excel hoặc tải lên Google Drive. |
| `csv/01-tong-quan.csv` | Số bài kế hoạch theo kênh và theo tuần, vai trò kênh phụ, phân bổ ngân sách quảng cáo. |
| `csv/02-master-checklist.csv` | **166 dòng nội dung** của cả chiến dịch (FB 70, IG 70, TikTok 14, Threads 8, YouTube 4): mã bài, kênh, thông điệp, góc khai thác, định dạng, tuần, ngày đăng, hạn gửi duyệt, lô duyệt, trạng thái, link bài nháp. |
| `csv/03-timeline.csv` | Mốc thời gian các hạng mục và bảng lô duyệt 1A, 1B, 2, 3, 4. |
| `csv/04-cac-dau-moi-quan-trong.csv` | Danh sách tài liệu quan trọng: tên, nội dung, lần sửa gần nhất, link. |
| `csv/05-kol-koc-dau-moi.csv` | KOL/KOC, người chia sẻ cho chuỗi Bảo tàng bóng đêm, BTC và mentor. |
| `ban-cu-Watts-up-Tracking-file-da-dien.xlsx` | File .xlsx cũ trước khi chuyển sang Google Sheet. **Không dùng để làm việc**, chỉ để đối chiếu. |

CSV chỉ chứa giá trị (không có công thức), lưu UTF‑8. Mở bằng Excel: *Data → From Text/CSV → File origin: 65001 (UTF‑8)* để không lỗi dấu tiếng Việt.

---

## Link gốc (bản đang dùng)

| Tài liệu | Link |
|---|---|
| Trang tính chính (Tracking file) | https://docs.google.com/spreadsheets/d/1RxB2wJoVkjJff7q1NxxsUZAV5EJvPnEsrAGWI2qvn1Y/edit |
| Cẩm nang marketing & storytelling | https://docs.google.com/document/d/1A_wubRYK_LxQNJibXxtGih1lgF3w9qpx-l01pf24low/edit |
| ↳ Tab Chiến dịch IMC | https://docs.google.com/document/d/1A_wubRYK_LxQNJibXxtGih1lgF3w9qpx-l01pf24low/edit?tab=t.mvd7mdlufnek |
| Bản thảo content tuần 1 | https://docs.google.com/document/d/1IASlPbBdp95y8POatRwIgCaaCDhC0cFOHVzYTdnK2jA/edit |
| Góp ý kịch bản phim (Google Docs) | https://docs.google.com/document/d/1zXCKQmGvaelMw9OvuG7BeXcWirwYTfKeFXwVorxS0Pc/edit |
| Tổng hợp góp ý chuyên gia & câu hỏi cần duyệt | https://claude.ai/artifact/MZUuYRzaQBrjhYfkXyTcCj |
| Thể lệ cuộc thi | https://setp.vn/vi/cuoc-thi-watts-up/ |

Kịch bản phim gốc của đội không nằm trong repo (đội tự giữ); link có trong `tracking/csv/04-cac-dau-moi-quan-trong.csv`.

---

## Đưa repo về máy local

Repo để **private**, nên máy cần đăng nhập đúng tài khoản GitHub `nguyenhoangvietdp-collab`.

### Cách 1 – Không dùng dòng lệnh (dễ nhất)
1. Mở repo trên GitHub → nút xanh **Code** → **Download ZIP**.
2. Giải nén ra thư mục bạn muốn, ví dụ `C:\Users\Admin\Desktop\VH_PROJECT_2016\WATTUP\fireflies`.

Cách này không tự cập nhật; lần sau muốn bản mới thì tải ZIP lại.

### Cách 2 – GitHub Desktop
1. Cài [GitHub Desktop](https://desktop.github.com/) và đăng nhập.
2. **File → Clone repository** → chọn `nguyenhoangvietdp-collab/fireflies` → chọn thư mục → **Clone**.
3. Khi có thay đổi trên GitHub, bấm **Fetch origin → Pull** để cập nhật.

### Cách 3 – Dòng lệnh (Git)
```bash
cd C:\Users\Admin\Desktop\VH_PROJECT_2016\WATTUP
git clone https://github.com/nguyenhoangvietdp-collab/fireflies.git
cd fireflies
git pull            # những lần sau, để lấy bản mới nhất
```

Muốn lưu thay đổi của mình lên lại GitHub:
```bash
git add .
git commit -m "Cập nhật ..."
git push
```

---

## Dùng các skill với Claude

Mỗi skill là một thư mục chứa `SKILL.md`. Claude đọc phần `name` và `description` ở đầu file để biết khi nào tự dùng skill.

### Claude Code (trên máy)
Chép **cả thư mục** skill (không chỉ file SKILL.md) vào thư mục skills của Claude:

| Phạm vi | Windows | macOS / Linux |
|---|---|---|
| Dùng cho mọi dự án | `%USERPROFILE%\.claude\skills\` | `~/.claude/skills/` |
| Chỉ dùng trong một dự án | `<thư mục dự án>\.claude\skills\` | `<thư mục dự án>/.claude/skills/` |

Windows (PowerShell), đứng trong thư mục `fireflies`:
```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\.claude\skills" | Out-Null
Copy-Item -Recurse -Force .\skills\copywriting-vi-en   "$env:USERPROFILE\.claude\skills\"
Copy-Item -Recurse -Force .\skills\wattsup-copywriting "$env:USERPROFILE\.claude\skills\"
```

macOS / Linux:
```bash
mkdir -p ~/.claude/skills
cp -r skills/copywriting-vi-en skills/wattsup-copywriting ~/.claude/skills/
```

Kết quả đúng sẽ là `~/.claude/skills/wattsup-copywriting/SKILL.md` (có một tầng thư mục mang tên skill).

Sau đó mở lại Claude Code, gõ `/skills` để kiểm tra đã thấy 2 skill. Cách dùng:
- Gọi thẳng: `/wattsup-copywriting viết caption FB cho bài poster kiến thức về đom đóm`
- Hoặc chỉ cần nói tự nhiên ("rà soát giúp caption này theo chuẩn chiến dịch"), Claude sẽ tự chọn skill phù hợp.

Gợi ý: mở Claude Code ngay trong thư mục `fireflies` để Claude đọc được cả cẩm nang, bản thảo và tracking khi viết bài.

### Claude trên web / app (claude.ai)
1. Nén **từng thư mục** skill thành file ZIP (ví dụ `wattsup-copywriting.zip`, bên trong là thư mục `wattsup-copywriting/SKILL.md`).
2. Vào **Settings → Capabilities → Skills → Upload skill**, chọn file ZIP.
3. Bật skill vừa tải lên.

### Khi nào dùng skill nào
- Viết bài cho chiến dịch "Một đêm đúng nghĩa" → `wattsup-copywriting`.
- Dự án khác, hoặc cần chuyển ngữ Việt ↔ Anh chung chung → `copywriting-vi-en`.

---

## Cập nhật repo khi tài liệu gốc thay đổi

Repo không tự đồng bộ với Google Docs/Sheets. Khi bản gốc thay đổi nhiều:
- **Google Docs**: *Tệp → Tải xuống → Microsoft Word (.docx)* (hoặc *Markdown (.md)*), ghi đè file tương ứng trong `tai-lieu/`.
- **Google Sheet**: *Tệp → Tải xuống → Microsoft Excel (.xlsx)*, ghi đè `tracking/Tracking-file-Google-Sheet.xlsx`.
- Commit và push (hoặc nhờ Claude làm việc này).
