---
tags:
  - workflow
  - playbook
  - project-management
  - 204prod
  - team-guide
created: 2026-06-30
updated: 2026-06-30
category: Media Production
---

# 🎬 204prod — Project Workflow Playbook

> **Dành cho cả team:** Cầm cái này lên là biết phải làm gì ở mỗi dự án, không cần đoán mò.
> 
> Dùng kèm với tài liệu chi tiết: [[204prod - Quy trình Sản xuất Video Chuyên nghiệp]]

---

## 📋 1. Project Types at 204prod

Mỗi loại dự án có quy trình riêng. Xác định loại project trước khi bắt đầu:

| Loại | Ví dụ | Thời gian điển hình | Ai lead? |
|:-----|:------|:-------------------|:---------|
| **🅰️ TVC / Video Quảng Cáo** | TVC sản phẩm, Brand film | 2–4 tuần | Creative Director |
| **🅱️ Social Content (Reels/Shorts/TikTok)** | Content daily, Trend video | 1–3 ngày | Content Lead |
| **🅲️ Photo / Campaign Shoot** | Lookbook, Sản phẩm, Event | 3–7 ngày | Photographer Lead |
| **🅳️ Motion Graphics / Animation** | Explainer, Logo animation | 5–14 ngày | Motion Designer |
| **🅴️ Hybrid (Video + Photo + Graphic)** | Full campaign | 3–6 tuần | Project Manager |

---

## ✅ 2. THE ACTUAL WORKFLOW — Từ A đến Z

Mỗi dự án đều đi qua **5 giai đoạn** này. ✅ là việc phải làm, 🟡 là bàn giao (bắt buộc có trước khi sang giai đoạn tiếp theo).

---

### 🟢 GIAI ĐOẠN 0: KICKOFF & BRIEF
> **Người chịu trách nhiệm:** Project Manager / Executive Producer

**Mục tiêu:** Xác định rõ khách hàng muốn gì trước khi ai làm gì.

- [ ] **K0.1** Gặp khách / nhận brief từ khách hàng
- [ ] **K0.2** Điền **Creative Brief** (điền mẫu bên dưới)
- [ ] **K0.3** Xác định loại dự án (A/B/C/D/E)
- [ ] **K0.4** Xác định deadline + ngân sách
- [ ] **K0.5** Assign team members cho từng vai trò
- [ ] 🟡 **Bàn giao:** Brief đã được duyệt → file `01_PRE_PRODUCTION/00_Brief_v1.pdf`

---

### 🔵 GIAI ĐOẠN 1: TIỀN KỲ (Pre-Production)
> **Lead:** Creative Director / Content Lead

- [ ] **1.1** Viết kịch bản (Script) → Creative team
- [ ] **1.2** Lên Shot List → DP / Cameraman
- [ ] **1.3** Vẽ Storyboard (nếu là TVC / Hybrid)
- [ ] **1.4** Tạo Moodboard (Pinterest, Refer) → gửi khách duyệt
- [ ] **1.5** Location Scouting & Casting (nếu cần)
- [ ] **1.6** Lên Call Sheet (lịch quay chi tiết)
- [ ] **1.7** Technical Specs: Chốt codec, fps, resolution, color space
- [ ] 🟡 **Bàn giao:** `01_PRE_PRODUCTION/` gồm:
  - `Script_v1.docx`
  - `Shot_List.xlsx`
  - `Moodboard.pdf`
  - `Call_Sheet.pdf`
  - `Tech_Specs.pdf`

---

### 🟡 GIAI ĐOẠN 2: SẢN XUẤT (Production / Shoot Day)
> **Lead:** DP / Production Manager

#### 🕐 Trước ngày quay (H-1):
- [ ] **2.0a** Kiểm tra thiết bị: pin, thẻ nhớ, ống kính, gimbal
- [ ] **2.0b** Format tất cả thẻ nhớ (đã backup nếu có dữ liệu cũ)
- [ ] **2.0c** Đồng bộ timecode (Tentacle Sync)
- [ ] **2.0d** Gửi Call Sheet cho cả ekip

#### 🎬 Ngày quay:
- [ ] **2.1** Check-in cả ekip, điểm danh
- [ ] **2.2** Setup ánh sáng theo sơ đồ
- [ ] **2.3** Quay take đầu → DP kiểm tra exposure, focus, WB
- [ ] **2.4** Quay theo Shot List
- [ ] **2.5** **DIT (bắt buộc):** 
  - Copy footage từ thẻ → SSD (bản 1)
  - Copy từ SSD → HDD/ổ cứng dự phòng (bản 2)
  - Đánh dấu circled takes vào Camera Report
- [ ] **2.6** QC footage: kiểm tra focus, audio, WB ngay tại trường
- [ ] **2.7** Thu âm: kiểm tra Lav + Boom, ghi WAV 24-bit/48kHz
- [ ] 🟡 **Bàn giao:** 
  - Toàn bộ footage gốc (ít nhất 2 bản)
  - `Camera_Report.xlsx`
  - `Audio_Log.txt`

---

### 🟣 GIAI ĐOẠN 3: HẬU KỲ (Post-Production)
> **Lead:** Editor

#### 🗂️ Ingestion (Ngay sau khi có footage):
- [ ] **3.1** Tạo thư mục dự án theo template chuẩn
- [ ] **3.2** Transcode proxy (nếu RAW/10-bit → ProRes Proxy 1080p)
- [ ] **3.3** Đồng bộ audio (timecode hoặc waveform sync)
- [ ] **3.4** Import vào DaVinci Resolve / Premiere

#### ✂️ Dựng:
- [ ] **3.5** Rough Cut (dựng thô) → đúng kịch bản
- [ ] **3.6** Gửi rough cut cho đạo diễn / PM duyệt
- [ ] **3.7** Fine Cut (dựng tinh) → chỉnh pacing, frame-accurate
- [ ] **3.8** 🔒 **Picture Lock** → không sửa hình nữa

#### 🎨 Làm màu & Hiệu ứng:
- [ ] **3.9** Color Correction (match camera, cân bằng exposure)
- [ ] **3.10** Color Grading (phong cách màu)
- [ ] **3.11** VFX / Motion Graphics (lower thirds, intro)

#### 🔊 Âm thanh:
- [ ] **3.12** Dialogue clean (noise reduction)
- [ ] **3.13** SFX / Foley (thêm tiếng động)
- [ ] **3.14** Music (chọn nhạc nền, cắt theo cao trào)
- [ ] **3.15** Audio Mix (cân bằng -14 LUFS cho social)

#### 📤 Review:
- [ ] **3.16** Export draft → upload Frame.io
- [ ] **3.17** Gửi link review cho team + khách hàng
- [ ] **3.18** Nhận feedback, sửa → v2, v3...
- [ ] **3.19** ✅ **Client Approved**
- [ ] 🟡 **Bàn giao:** Timeline đã Picture Lock + Mixdown

---

### 🟤 GIAI ĐOẠN 4: BÀN GIAO & LƯU TRỮ (Delivery & Archive)
> **Lead:** Editor / PM

- [ ] **4.1** Export master: ProRes 422 HQ (lưu trữ)
- [ ] **4.2** Export delivery: H.264/MP4 (giao khách, social)
- [ ] **4.3** Upload bản delivery cho khách (MASV / Google Drive / Wetransfer)
- [ ] **4.4** Archive project: DaVinci/Project Manager → gom all source
- [ ] **4.5** Dọn file rác, nén thư mục project
- [ ] **4.6** Đẩy archive lên Backblaze B2 / NAS
- [ ] **4.7** Gửi email bàn giao + invoice cho khách
- [ ] 🟡 **Hoàn thành** ✅

---

## 👥 3. Role & Responsibility Matrix

| Vai trò | Viết tắt | Trách nhiệm chính | Giai đoạn |
|:--------|:---------|:------------------|:----------|
| **[Executive Producer](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#executive-producer-ep---nhà-sản-xuất-điều-hành)** | EP | Hoạch định ngân sách, pháp lý, duyệt dự án vĩ mô | 0, 4 |
| **[Project Manager](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#pm-project-manager---quản-lý-dự-án)** | PM | Lên lịch, giao việc, đốc tiến độ, liên hệ khách | 0, 1, 4 |
| **[Producer](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#producer---sản-xuất)** | PR | Điều hành ngân sách thực tế, logistic, nhân sự set quay | 1, 2 |
| **[Creative Director](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#cd-creative-director---giám-đốc-sáng-tạo)** | CD | Ý tưởng, kịch bản, moodboard, định hướng sáng tạo | 1 |
| **[Đạo diễn / Director](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#đạo-diễn-director)** | DIR | Chỉ đạo diễn xuất, quyết định nghệ thuật hiện trường | 2 |
| **[DOP / Cameraman](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#dop-director-of-photography---đạo-diễn-hình-ảnh)** | DOP | Thiết kế ánh sáng, góc máy, vận hành máy quay | 2 |
| **[Media](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#media---phóng-viên-ảnh--chuyên-viên-truyền-thông)** | MED | Quay/chụp nhanh, hậu trường, quản trị kênh social | 2, 4 |
| **[Editor](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#video-editor---biên-tập-dựng-phim)** | ED | Dựng thô → tinh, proxy workflow, khóa hình | 3 |
| **[Colorist](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#colorist---chuyên-viên-chỉnh-màu)** | CL | Color correction + grading | 3 |
| **[VFX / Sound Designer](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#sound-designer--mixer---thiết-kế--hòa-âm)** | VFX/SD | Đồ họa, animation, xử lý tạp âm, mix âm thanh | 3 |
| **[Account](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#account---quản-trị-quan-hệ-khách-hàng)** | ACC | Làm việc khách hàng, chăm sóc hợp đồng, nghiệm thu | 0, 4 |
| **[Quality Advisor](../03-Team-Guidelines/02%20-%20Vai%20tro%20va%20Nhiem%20vu.md#quality-advisor---cố-vấn-chất-lượng)** | QA | Cố vấn, duyệt chất lượng bản nháp cuối trước khi giao | 3, 4 |

> 📌 **Small team rule:** 1 người có thể đảm nhiệm nhiều vai trò. Ví dụ: Editor có thể kiêm Colorist và Sound Designer. Nhưng **không ai bỏ qua bước** — chỉ là 1 người làm nhiều bước.

---

## 📁 4. Folder Template (Copy-Paste Ready)

Mỗi dự án mới → tạo folder theo cấu trúc này:

```
📁 [TEN_DU_AN]_[YYYYMMDD]/
├── 📁 01_PRE_PRODUCTION/
│   ├── 📄 00_Brief_v1.pdf
│   ├── 📄 Script_v1.docx
│   ├── 📄 Shot_List.xlsx
│   ├── 📄 Moodboard.pdf
│   ├── 📄 Call_Sheet.pdf
│   └── 📄 Tech_Specs.pdf
├── 📁 02_FOOTAGE/
│   ├── 📁 CAM_A/
│   ├── 📁 CAM_B/
│   └── 📁 DRONE/
├── 📁 03_AUDIO/
│   ├── 📁 FIELD_RECORD/
│   ├── 📁 VOICE_OVER/
│   ├── 📁 MUSIC/
│   └── 📁 SFX/
├── 📁 04_PROJECT_FILES/
│   ├── 📁 DaVinci_Resolve/
│   └── 📁 After_Effects/
├── 📁 05_ASSETS/
│   ├── 📁 Logo/
│   ├── 📁 Font/
│   └── 📁 Templates/
├── 📁 06_EXPORTS/
│   ├── 📁 Draft_v1/
│   ├── 📁 Draft_v2/
│   └── 📁 Final/
└── 📁 07_DELIVERY/
    └── 📄 [TEN_DU_AN]_Final_H264.mp4
```

---

## 📝 5. Creative Brief Template (Điền cho mỗi dự án)

```markdown
# CREATIVE BRIEF — [Tên dự án]

## 1. THÔNG TIN CƠ BẢN
- **Khách hàng:** 
- **Loại dự án:** TVC / Social / Photo / Motion / Hybrid
- **Deadline:** 
- **Ngân sách:** 
- **PM:** 
- **Team assigned:** 

## 2. MỤC TIÊU
- Thông điệp chính muốn truyền tải:
- Đối tượng mục tiêu:
- Nền tảng phân phối (YouTube / TikTok / Facebook / TV):

## 3. YÊU CẦU SÁNG TẠO
- Tone & Feel (vui / cảm động / nghiêm túc / trẻ trung):
- Màu sắc chủ đạo:
- Âm nhạc gợi ý:
- Tham khảo (link):

## 4. LOGISTICS
- Địa điểm quay:
- Diễn viên:
- Thời gian quay dự kiến:
- Thiết bị đặc biệt (drone, gimbal, crane, etc.):

## 5. PHÊ DUYỆT
- [ ] Khách hàng duyệt brief
- [ ] Duyệt kịch bản
- [ ] Duyệt sản phẩm cuối
```

---

## ⚡ 6. Quick Reference: Flowchart

```
KHÁCH GỬI BRIEF
      │
      ▼
K0: KICKOFF ──► Phân loại dự án ──► Assign team
      │
      ▼
K1: TIỀN KỲ ──► Script → Shot List → Moodboard → Location
      │
      ▼
K2: SẢN XUẤT ──► Chuẩn bị → Quay → DIT (3-2-1 backup) → QC
      │
      ▼
K3: HẬU KỲ ──► Proxy → Dựng → Picture Lock → Color → Sound → Review
      │
      ▼
K4: GIAO HÀNG ──► Export → Upload → Archive → Invoice
      │
      ▼
      ✅ DONE
```

---

## 🚨 7. Common Pitfalls & How to Avoid

| Vấn đề | Hậu quả | Cách tránh |
|:-------|:---------|:-----------|
| Không có brief rõ ràng | Làm đi làm lại, mất thời gian | **Ép khách duyệt brief trước khi làm bất cứ gì** |
| Quên format thẻ nhớ | Hết dung lượng giữa chừng | Checklist trước ngày quay (bước 2.0b) |
| Mất footage | Thảm họa | **DIT 3-2-1 backup — không bao giờ bỏ qua** |
| Chỉnh màu trước Picture Lock | Làm lại toàn bộ | **🔒 Picture Lock xong mới chuyển colorist** |
| Giao file sai format | Khách không mở được | Hỏi khách: "Anh/chị cần file gì? MP4 hay ProRes?" |
| Quên archive dự án | Sau này không tìm được để chỉnh sửa | Sau bàn giao: **bắt buộc archive trong 24h** |

---

## 📎 8. Liên kết

- [[204prod - Quy trình Sản xuất Video Chuyên nghiệp]] — Tài liệu chi tiết về kỹ thuật từng giai đoạn
- [[Duy Phúc Profile]]