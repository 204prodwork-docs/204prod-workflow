---
tags:
  - workflow
  - 204prod
  - team-guide
  - onboarding
created: 2026-06-30
category: Media Production
---

# 🎬 204.prod — Project Playbook (Hướng dẫn quy trình cho team)

> **Mục tiêu:** Giúp mọi người trong team — từ người mới đến cũ — biết chính xác phải làm gì ở mỗi giai đoạn của dự án, ai chịu trách nhiệm, và bàn giao cái gì.

---

## 🌐 Tổng quan: Vòng đời một dự án

Mỗi dự án của 204.prod đi qua **6 giai đoạn** rõ ràng. Mỗi giai đoạn kết thúc bằng một **cột mốc bàn giao (deliverable)** — không có bàn giao là chưa xong giai đoạn.

```
[BÁO GIÁ] → [TIỀN KỲ] → [SẢN XUẤT] → [HẬU KỲ] → [DUYỆT] → [BÀN GIAO & LƯU TRỮ]
```

---

## 1. 📋 Báo giá & Kickoff (1–2 ngày)

**Mục tiêu:** Xác định rõ việc cần làm, báo giá, và nhận deposit trước khi làm.

| Ai làm | Công việc | Bàn giao |
|--------|-----------|----------|
| **PM / Founder** | Trao đổi với khách hàng: mục tiêu video, đối tượng, thời lượng, deadline, budget | Brief khách hàng (file Google Doc) |
| **PM** | Lên quote + gửi hợp đồng | Hợp đồng đã ký + 50% deposit |

**🔑 Key rule:** KHÔNG bắt đầu Tiền kỳ khi chưa có deposit.

✅ **Cột mốc:** Brief đã approve + Hợp đồng đã ký.

---

## 2. ✏️ Tiền kỳ (Pre-Production) — 2–5 ngày

**Mục tiêu:** Có đủ tài liệu để tổ sản xuất bấm máy mà không phải hỏi lại.

### Các bước cụ thể:

| Bước | Ai làm | Chi tiết | Bàn giao |
|------|--------|----------|----------|
| **2a. Kịch bản (Script)** | Creative / Copywriter | Viết kịch bản văn học + lời thoại. Gửi khách duyệt. | Script vFinal (Google Doc) |
| **2b. Shotlist + Storyboard** | Director / DP | Phân tích từng góc máy. Nếu dùng moodboard, đính kèm tham khảo. | Shot list (Sheet) + Storyboard PDF |
| **2c. Technical Spec** | DP / Editor | Ghi rõ: resolution, frame rate, codec, color space. Gửi cho cả tổ quay. | Spec Sheet (1 trang) |
| **2d. Call Sheet** | PM | Lịch trình quay theo giờ: địa điểm, diễn viên, ekip, equipment. Gửi trước 24h. | Call Sheet (PDF) |
| **2e. Chuẩn bị thiết bị** | Camera / DIT | Kiểm tra pin, thẻ nhớ, lens, gimbal, thiết bị âm thanh. | Checklist đã check (form) |

**📂 Thư mục:** `📁 [Dự án]/01_PRE_PRODUCTION/`

✅ **Cột mốc:** Tất cả tài liệu trên đã hoàn thành + khách duyệt script.

---

## 3. 🎥 Sản xuất (Production) — 1–2 ngày quay

**Mục tiêu:** Quay đủ footage sạch, đúng spec, không mất dữ liệu.

### Phân công hiện trường:

| Vai trò | Ai giữ | Nhiệm vụ chính |
|---------|--------|----------------|
| **Director** | Đạo diễn | Chỉ đạo diễn xuất, đảm bảo mạch cảm xúc đúng brief |
| **DP / Cam** | Quay phim | Ánh sáng, bố cục, lấy nét — chụp camera report |
| **DIT** | *(ai đó giữ)* | Copy thẻ → 2 ổ cứng SSD → check file OK |
| **Âm thanh** | *(ai đó giữ)* | Boom + Lav ghi WAV 24-bit/48kHz, dùng Tentacle Sync nếu có |
| **PM / PA** | PM / PA | Giữ Call Sheet, đôn đốc lịch, lo hậu cần |

### Quy trình DIT (bắt buộc):

1. Hết thẻ → DIT nhận thẻ, copy vào **SSD số 1**
2. Verify file mở được bằng VLC / MediaInfo
3. Copy từ SSD số 1 → **SSD số 2** (backup tại chỗ)
4. Đánh dấu thẻ đã copy xong (băng dính màu / sticker)
5. Cuối ngày: mang **SSD số 2** về văn phòng / upload cloud

> **⚠️ KHÔNG** format thẻ cho đến khi có ít nhất 2 bản copy OK.

✅ **Cột mốc:** Toàn bộ footage đã ingest + 2 bản backup + camera report.

---

## 4. 💻 Hậu kỳ (Post-Production) — 2–7 ngày (tuỳ độ dài)

**Mục tiêu:** Có bản dựng hoàn chỉnh, sẵn sàng cho duyệt.

### Quy trình từng bước:

| Bước | Ai làm | Thời gian | Chi tiết |
|------|--------|-----------|----------|
| **4a. Ingest + Proxy** | Editor | Ngày 1 | Tạo cấu trúc thư mục, transcode proxy ProRes 422 Proxy / DNxHR LB 1080p |
| **4b. Rough Cut** | Editor | Ngày 1–2 | Dựng thô theo kịch bản — chọn selects, ghép nối |
| **4c. Fine Cut + Picture Lock** | Editor + Director | Ngày 2–3 | Tinh chỉnh pacing, chốt cut. **Sau Picture Lock không thay đổi edit nữa** |
| **4d. VFX / Motion** | Motion Designer | Song song 4c | Lower thirds, intro/outro, overlay, text animation |
| **4e. Color** | Colorist | Ngày 3–4 | Correction → Grading. Làm trên DaVinci Resolve |
| **4f. Sound** | Sound Designer | Ngày 3–4 | Làm sạch thoại, SFX, nhạc nền, mix xuống -14 LUFS |
| **4g. Export Draft** | Editor | Ngày 4 | Export H.264 draft, upload lên Frame.io hoặc Google Drive |

### 📂 Cấu trúc thư mục dự án:

```
📁 [PROJECT_NAME]/
├── 01_PRE_PRODUCTION/
├── 02_FOOTAGE/
│   ├── CAM_A/
│   ├── CAM_B/
│   └── DRONE/
├── 03_AUDIO/
│   ├── FIELD_RECORD/
│   ├── VOICE_OVER/
│   ├── MUSIC/
│   └── SFX/
├── 04_PROJECT_FILES/
├── 05_ASSETS/
├── 06_EXPORTS/
│   ├── DRAFT_v1/
│   ├── DRAFT_v2/
│   └── FINAL/
└── 07_DELIVERY/
```

✅ **Cột mốc:** Export draft (H.264) + link Frame.io gửi duyệt.

---

## 5. ✅ Duyệt & Sửa (Review & Revisions) — 1–3 ngày

**Mục tiêu:** Khách duyệt Final Cut — không còn sửa sau đó.

| Bước | Ai làm | Công việc |
|------|--------|-----------|
| **5a. Review nội bộ** | Director + PM | Xem trước khi gửi khách. Check: lỗi chính tả, sync âm, màu sắc |
| **5b. Gửi duyệt** | PM | Gửi link Frame.io / Google Drive cho khách. Ghi rõ hạn reply |
| **5c. Nhận feedback** | PM | Tổng hợp comment từ khách, phân loại: **phải sửa** vs **nên sửa** vs **tuỳ chọn** |
| **5d. Sửa (v2, v3...)** | Editor | Sửa theo feedback. Mỗi vòng sửa tối đa **1–2 ngày** |
| **5e. Final Approval** | PM | Confirm với khách = **"Final Cut Approved"** bằng văn bản |

> **💡 Mẹo:** Giới hạn số vòng sửa trong hợp đồng: "2 vòng sửa miễn phí, vòng 3+ tính phí."

✅ **Cột mốc:** Khách gửi xác nhận Final Cut Approved.

---

## 6. 📦 Bàn giao & Lưu trữ — 1 ngày

**Mục tiêu:** Giao đúng định dạng + dọn dẹp lưu trữ cho lần sau.

| Bước | Ai làm | Công việc |
|------|--------|-----------|
| **6a. Export final** | Editor | Xuất 2 bản: (1) H.264/MP4 cho giao hàng, (2) ProRes 422 HQ cho lưu trữ |
| **6b. Gửi khách** | PM | Gửi link tải (Google Drive / MASV) + hoá đơn thanh toán phần còn lại |
| **6c. Archive dự án** | Editor | Dùng DaVinci Resolve Project Archive → gom tất cả source. Nén + đẩy lên cold storage (Backblaze B2 / NAS) |
| **6d. Dọn workspace** | Editor | Xoá proxy, cache, file tạm để giải phóng dung lượng |

✅ **Cột mốc:** Thanh toán đủ + dự án archived.

---

## 🧭 Cheat Sheet cho người mới

> *"Em mới vào team — em cần biết gì?"*

### Việc đầu tiên khi nhận dự án mới:
1. Kiểm tra **Brief** và **Script** trong thư mục `01_PRE_PRODUCTION/`
2. Xem **Shotlist** để biết cần quay gì
3. Nếu là Editor: check **Technical Spec** để biết codec, resolution, proxy setup

### Ai hỏi ai?

| Nếu cần... | Hỏi... |
|------------|--------|
| Kịch bản, thông điệp | **Director / Creative** |
| Kỹ thuật quay, lens, codec | **DP** |
| Lịch, khách hàng, budget | **PM** |
| Dựng, proxy, màu, âm thanh | **Editor Lead** |
| Thiết bị, thẻ nhớ, backup | **DIT** |

### Các thuật ngữ cần biết:

| Thuật ngữ | Nghĩa |
|-----------|-------|
| **Picture Lock** | Cut đã chốt — không sửa timeline nữa |
| **Proxy** | Bản footage nhẹ (1080p) để dựng mượt, sẽ relink sang file gốc khi render |
| **ACES** | Hệ thống quản lý màu chuẩn — giúp các camera khác nhau lên màu giống nhau |
| **Frame.io** | Nền tảng review video — khách comment trực tiếp lên video theo timecode |
| **DIT** | Người copy & verify footage tại hiện trường |
| **-14 LUFS** | Chuẩn loudness cho YouTube/social media |

---

## 📋 Template Checklist

> *Copy cái này vào mỗi dự án mới, check dần khi hoàn thành.*

### Tiền kỳ
- [ ] Brief khách duyệt
- [ ] Script vFinal
- [ ] Shotlist + Storyboard
- [ ] Technical Spec
- [ ] Call Sheet gửi ekip trước 24h
- [ ] Thiết bị checked

### Sản xuất
- [ ] Camera report từng thẻ
- [ ] DIT: 2 bản backup OK
- [ ] Field audio WAV 24-bit
- [ ] Timecode sync (nếu có thiết bị)

### Hậu kỳ
- [ ] Cấu trúc thư mục tạo
- [ ] Proxy transcode done
- [ ] Rough Cut done
- [ ] Picture Lock chốt
- [ ] VFX / Motion inserted
- [ ] Color Correction + Grading
- [ ] Sound Design + Mix (-14 LUFS)
- [ ] Export draft gửi duyệt

### Duyệt
- [ ] Review nội bộ
- [ ] Khách duyệt v1
- [ ] Sửa feedback
- [ ] Final Cut Approved

### Bàn giao
- [ ] Export H.264 delivery
- [ ] Export ProRes master
- [ ] Gửi link + hoá đơn cho khách
- [ ] Archive dự án
- [ ] Dọn workspace

---

*Tài liệu này được tạo tối 30/06/2026 theo yêu cầu của Duy Phúc. Team có thể in / share để mọi người nắm quy trình.*

*Tham khảo thêm quy trình kỹ thuật chi tiết: [[204.prod - Quy trình Sản xuất Video Chuyên nghiệp]]*