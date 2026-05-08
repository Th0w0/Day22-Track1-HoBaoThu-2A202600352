# Document Trail — VoiceFirst AI for Teachers
**Date:** 09/05/2026

---

# Bảng đối chiếu 5 loại hồ sơ

| # | Loại | Status | Link/Path | Deadline build |
|---|------|--------|-----------|----------------|
| 1 | Nhật ký kiểm thử Voice AI & classroom workflow | ✗ | `/compliance/voice_ai_testing_log.md` | 15/05/2026 |
| 2 | Hồ sơ rà soát điều khoản vendor | ✗ | `/legal/vendor_terms_review.md` | 18/05/2026 |
| 3 | Nhật ký giám sát hoạt động bất thường | ✗ | `/risk/abnormal_activity_monitoring.md` | 25/05/2026 |
| 4 | DPIA / CTIA | ✗ | `/privacy/dpia_ctia_v1.md` | 20/05/2026 |
| 5 | Phê duyệt nội dung marketing | ✗ | `/marketing/claim_approval_log.md` | 12/05/2026 |

---

# Giải thích từng loại hồ sơ

## 1. Nhật ký kiểm thử Voice AI & classroom workflow

### Mục đích
Chứng minh founder:
- đã kiểm thử Voice AI trước khi public
- không cố tình overclaim khả năng AI
- có benchmark về speech recognition và latency
- hiểu limitation của classroom automation

### Liên quan rủi ro
- speech recognition sai
- voice command fail
- LMS trigger nhầm
- attendance automation lỗi
- AI misunderstanding trong lớp học

### Với VoiceFirst AI đặc biệt quan trọng vì:
Sản phẩm đang bán:
- classroom automation
- voice interaction
- AI teaching assistant
- hands-free classroom workflow

=> nếu claim vượt khả năng thực tế rất dễ thành legal/compliance risk.

---

## 2. Hồ sơ rà soát điều khoản vendor

### Vendor hiện tại có khả năng gồm:
- OpenAI
- Whisper / FasterWhisper providers
- Azure Speech
- AWS/Azure/GCP
- LMS providers
- monitoring tools

### Mục tiêu
Chứng minh:
- founder đã review vendor risk
- hiểu voice data có ra nước ngoài không
- hiểu liability limitation
- hiểu audio retention policy
- hiểu dữ liệu transcript được lưu thế nào

### Risk thực tế
Vendor thay policy nhưng startup:
- không biết
- không update customer disclosure
- vẫn marketing sai về privacy/security

---

## 3. Nhật ký giám sát hoạt động bất thường

### Với VoiceFirst AI:
Không phải AML trực tiếp,
nhưng vẫn nên có:
- abnormal classroom usage monitoring
- suspicious admin activity
- unusual LMS access
- mass export/download
- abuse detection
- suspicious microphone activity

### Vì sao cần?
Voice AI classroom systems rất dễ:
- bị misuse
- bị internal abuse
- bị unauthorized recording
- bị data exfiltration
- bị prompt injection qua voice interaction

---

## 4. DPIA / CTIA

## Mục tiêu
Chứng minh:
- startup hiểu data flow
- biết có cross-border transfer
- đã đánh giá impact privacy
- hiểu rủi ro của voice data

### Với VoiceFirst AI:
Rủi ro cao vì:
- dùng OpenAI / cloud speech APIs
- xử lý voice recordings
- xử lý transcript
- tích hợp LMS
- có dữ liệu giáo dục
- possible student information

### Đây gần như chắc chắn sẽ bị hỏi khi scale enterprise/school deployment.

---

## 5. Phê duyệt nội dung marketing

## Mục tiêu
Tránh:
- founder livestream claim quá mức
- sales deck oversell
- website wording misleading
- overclaim về speech recognition

### Đặc biệt nguy hiểm với Voice AI startup:
Vì Voice AI rất dễ:
- demo đẹp
- production fail trong môi trường ồn
- latency thay đổi theo mạng
- accuracy biến động theo accent/microphone

### Risk phrase cần tránh:
- “100% accurate speech recognition”
- “fully autonomous classroom”
- “zero privacy risk”
- “AI understands every classroom interaction”

---

# TOP 1 ưu tiên

## Loại:
#1 — Nhật ký kiểm thử Voice AI & classroom workflow

## Lý do:
VoiceFirst AI đang bán:
- classroom automation
- hands-free teaching
- AI voice interaction

=> nếu claim vượt khả năng thực tế mà không có evidence testing thì đây là legal/compliance risk lớn nhất hiện tại.

---

# Template build trong 1 tuần

## Người chịu trách nhiệm:
- Founder / Product Lead
- Voice AI Engineer
- Compliance Reviewer (part-time/advisor)

---

## Tần suất cập nhật:
- Mỗi feature voice AI mới
- Mỗi lần đổi STT model
- Mỗi lần đổi wake-word engine
- Hằng quý
- Trước demo lớn / school deployment

---

# Sample 3-5 dòng

```markdown
## Voice AI Testing Record

Feature: Voice-controlled Slide Navigation v1
Date tested: 09/05/2026
Model used: FasterWhisper small
Dataset: 120 classroom voice commands
Observed accuracy: 89.2%
Average latency: 780ms

Known limitations:
- giảm accuracy trong môi trường ồn
- khó nhận accent địa phương mạnh
- microphone quality ảnh hưởng lớn

Approved marketing wording:
“Supports hands-free classroom slide control”
NOT allowed:
“100% accurate classroom voice control”
```

# Recommended Supporting Documents

## Compliance
- AI governance policy
- Classroom privacy notice
- Audio retention policy
- Vendor risk matrix
- Voice data access policy

---

## Technical
- STT benchmark logs
- Latency testing logs
- Classroom noise test report
- LMS integration audit
- Security review checklist

---

## Procurement
- School deployment checklist
- Teacher onboarding SOP
- Incident response workflow
- Classroom rollback procedure
- Voice recording disclosure form

---

# Suggested Folder Structure

```txt
/compliance
    voice_ai_testing_log.md
    ai_governance_policy.md

/legal
    vendor_terms_review.md
    school_dpa_template.md

/privacy
    dpia_ctia_v1.md
    audio_retention_policy.md

/risk
    abnormal_activity_monitoring.md
    classroom_incident_log.md

/marketing
    claim_approval_log.md
    approved_wording_list.md

```

# Quick Governance Priorities

## Priority 1
Voice AI testing evidence

## Priority 2
DPIA / CTIA cho voice data

## Priority 3
Vendor review cho STT / cloud providers

## Priority 4
Marketing wording approval

## Priority 5
Classroom incident monitoring

---

# Final Notes

VoiceFirst AI for Teachers hiện phù hợp với:
- smart classroom
- classroom workflow automation
- AI teaching assistant
- LMS-integrated voice workflows

Tuy nhiên chưa nên claim:
- “fully autonomous classroom”
- “100% accurate speech recognition”
- “zero privacy risk”
- “AI replaces teachers”

Ưu tiên hiện tại:
- build governance documentation
- build testing evidence
- review vendor/privacy risks
- chuẩn hóa marketing wording
- chuẩn bị procurement-ready compliance package