# Territorial Scope — VoiceFirst AI for Teachers

**Date:** 09/05/2026

---

# 1. Product Context

## Product

VoiceFirst AI for Teachers — trợ lý AI điều khiển lớp học bằng giọng nói dành cho giáo viên.

Hệ thống hoạt động như:

* voice classroom assistant
* speech-to-text (STT)
* slide control bằng giọng nói
* LMS orchestration
* attendance form generation
* classroom question form generation
* QR attendance interaction
* teaching workflow automation

## Mục tiêu chính

Giúp giáo viên:

* chuyển slide không cần chạm máy tính
* mở bài giảng bằng giọng nói
* tạo form điểm danh nhanh
* tạo form câu hỏi / quiz ngay trong lớp
* tích hợp trực tiếp với LMS
* giảm thao tác thủ công trong quá trình giảng dạy

## Mục tiêu chính

Giúp người dùng:

* điều khiển hệ thống bằng giọng nói
* giảm thao tác thủ công
* tăng accessibility
* hỗ trợ giáo viên vận hành lớp học nhanh hơn
* tích hợp AI voice vào workflow học tập / làm việc

---

# 2. Customer / Segment Context

## Khách hàng mục tiêu

### Giáo dục

* trường đại học
* trường phổ thông
* trung tâm đào tạo
* edtech platforms

### Doanh nghiệp

* smart office
* training center
* enterprise internal assistant

## Use-case chính

* chuyển slide bằng voice command
* mở file bài giảng
* tạo form điểm danh tự động
* tạo QR attendance
* tạo form câu hỏi nhanh trong lớp
* tích hợp LMS
* classroom voice assistant

## Người mua chính

* School IT Department
* CIO / CTO
* Academic Affairs Office
* EdTech Operations

## Người duyệt ngân sách

* Ban giám hiệu
* School Board
* Procurement Office
* Compliance / Security team

## Đặc điểm compliance quan trọng

Hệ thống:

* xử lý voice commands của giáo viên
* tích hợp LMS và classroom workflow
* lưu interaction logs
* có khả năng truy cập dữ liệu lớp học
* có automation liên quan học sinh / sinh viên

=> mức độ scrutiny về privacy, educational data protection và LMS security khá cao.

---

# 3. Câu hỏi 1: User EU?

## User EU hiện tại

* Chưa có evidence về EU users
* Current focus:

  * trường học Việt Nam
  * giáo dục nội bộ
  * doanh nghiệp Việt Nam

## Kế hoạch mở rộng EU

* Chưa có roadmap rõ ràng
* Focus hiện tại = Vietnam market

## Kết luận

### EU AI Act áp dụng hiện tại:

NOT YET

### Tuy nhiên có future risk:

Nếu:

* có người dùng EU
* có trường quốc tế tại EU
* hệ thống xử lý voice data của EU residents
* dùng AI để monitoring student activity

thì EU AI Act có thể áp dụng theo extraterritorial scope.

### Đánh giá mức độ:

* Current risk: Thấp
* Future expansion risk: Trung bình

---

# 4. Câu hỏi 2: Dữ liệu Việt Nam?

## Loại dữ liệu cá nhân đang xử lý

### 1. Thông tin định danh

* tên
* email trường học / doanh nghiệp
* student ID
* employee ID
* lớp học / phòng ban

### 2. Voice & classroom interaction data

* audio commands
* wake-word samples
* speech embeddings
* voice command history
* transcription text
* classroom interaction logs

### 3. LMS & classroom workflow data

* attendance logs
* LMS interaction history
* generated forms / quizzes
* classroom analytics
* slide interaction history

### 4. Metadata hệ thống

* IP address
* device info
* session data
* microphone metadata
* access logs

### 5. Dữ liệu nhạy cảm tiềm năng

Có thể chứa:

* giọng nói cá nhân
* thông tin học sinh
* thông tin giáo viên
* nội dung lớp học
* dữ liệu nội bộ doanh nghiệp

---

## Có chuyển dữ liệu ra nước ngoài?

LIKELY YES

## Dấu hiệu cross-border transfer

### AI inference

* OpenAI API
* Whisper / GPT APIs
* external speech models
* cloud AI inference services

### Cloud infrastructure

Có khả năng dùng:

* AWS
* Azure
* GCP
* HuggingFace endpoints

nằm ngoài Việt Nam.

### Voice processing / monitoring

Có thể lưu:

* audio files
* transcripts
* embeddings
* logs
* prompts / responses

ngoài Việt Nam.

---

## Kết luận PDPL

### PDPL áp dụng:

YES (gần như chắc chắn)

### CTIA / hồ sơ đánh giá tác động chuyển dữ liệu:

LIKELY YES

Đặc biệt vì:

* xử lý voice data
* có khả năng nhận diện cá nhân
* xử lý dữ liệu giáo dục
* dùng external AI providers
* có cross-border cloud processing

---

## Mức độ rủi ro dữ liệu

| Thành phần                      | Mức              |
| ------------------------------- | ---------------- |
| Voice biometric exposure        | Cao              |
| Cross-border transfer           | Cao              |
| Student data privacy            | Cao              |
| Audio retention risk            | Trung bình → Cao |
| AI-generated incorrect response | Trung bình       |
| Unauthorized recording          | Cao              |

---

## Nghĩa vụ compliance dự kiến

### Cần chuẩn bị:

* Privacy Notice
* Consent collection flow
* Audio retention policy
* Data Processing Agreement (DPA)
* Vendor/subprocessor disclosure
* Incident response process
* Human oversight policy
* Audit logging
* Voice recording disclosure

### Enterprise / trường học sẽ hỏi:

* audio có được lưu không?
* dữ liệu LMS có được truy cập bởi AI không?
* AI có truy cập danh sách học sinh không?
* có lưu transcript không?
* dữ liệu có ra nước ngoài không?
* có thể disable recording không?
* ai truy cập được logs?
* có audit trail không?
* có thể triển khai on-premise không?

---

# 5. Câu hỏi 3: Tầng rủi ro Luật AI VN?

## Phân loại

TRUNG BÌNH

---

## Lập luận

VoiceFirst AI for Teachers không trực tiếp:

* chấm điểm tự động
* quyết định học vụ
* thay giáo viên ra quyết định học thuật
* đánh giá pháp lý / tài chính

nên chưa thuộc nhóm “high-risk AI decision systems”.

Tuy nhiên hệ thống:

* điều khiển workflow lớp học
* tích hợp LMS
* truy cập dữ liệu học sinh / lớp học
* xử lý voice data
* có automation trong giáo dục
* ảnh hưởng trực tiếp teaching workflow

=> có governance impact đáng kể trong môi trường giáo dục.

Ngoài ra:

* voice command logging
* classroom monitoring
* attendance workflows
* AI interaction traceability

khiến hệ thống có yêu cầu governance và audit nhất định.

---

## Đánh giá theo use-case

| Use case                             | Tầng                 |
| ------------------------------------ | -------------------- |
| Voice-controlled classroom assistant | Trung bình           |
| AI attendance workflow               | Gần Cao              |
| Enterprise voice assistant           | Trung bình           |
| LMS-integrated teaching assistant    | Trung bình → Gần Cao |
| Accessibility assistant              | Thấp → Trung bình    |

---

## Nghĩa vụ tương ứng dự kiến

### Governance

* AI risk management
* voice data governance
* access logging
* incident management

### Transparency

* thông báo recording
* explainability cho AI actions
* audit logging

### Human oversight

* manual override
* admin approval workflow
* teacher control over automation

### Technical controls

* microphone permission management
* secure LMS integration
* secure voice storage
* role-based classroom access
* wake-word filtering
* audit logging
* rollback capability

### Compliance controls

* retention policy
* access control
* encryption
* security review

---

# 6. Procurement & Vendor Risk Reality

## Enterprise / School concern lớn nhất

Khách hàng sẽ đánh giá:

| Câu hỏi                           | Tại sao quan trọng          |
| --------------------------------- | --------------------------- |
| Có lưu audio không?               | privacy concern             |
| Voice data lưu ở đâu?             | PDPL risk                   |
| Có cross-border transfer không?   | legal risk                  |
| Có thể disable recording không?   | user consent                |
| Có audit trail không?             | accountability              |
| Có human override không?          | operational safety          |
| LMS integration có an toàn không? | educational data governance |
| Có support on-premise không?      | enterprise requirement      |
| Có mã hóa dữ liệu không?          | security                    |

---

## Risk lớn nhất commercial

VoiceFirst AI có thể bị reject không phải vì:

* chất lượng speech recognition

mà vì:

* privacy review
* school procurement
* phụ huynh concern
* data retention concern
* audio recording risk
* security assessment

---

# 7. Recommended Compliance Roadmap

## 0–30 ngày

* Data flow mapping
* Privacy Notice
* Audio consent flow
* Vendor inventory
* Recording disclosure policy
* Retention policy

## 30–90 ngày

* AI governance policy
* Human oversight SOP
* Audit logging
* Voice access control
* Security questionnaire package

## 90–180 ngày

* On-premise deployment option
* Cross-border transfer assessment
* Enterprise-ready compliance package
* Voice data anonymization layer
* Speaker verification safeguards

---

# 8. Các deadline cần theo dõi

* [ ] 1/1/2026 — PDPL + DTI Law hiệu lực
* [ ] 1/3/2026 — Luật AI VN hiệu lực
* [ ] 2/8/2026 — EU AI Act high-risk obligations
* [ ] 1/3/2027 — Hết giai đoạn ân hạn

---

# 9. Executive Summary

## Territorial Scope hiện tại

| Framework                            | Áp dụng    |
| ------------------------------------ | ---------- |
| PDPL Việt Nam                        | YES        |
| Cross-border transfer obligations    | LIKELY YES |
| EU AI Act                            | NOT YET    |
| VN AI Law                            | YES        |
| Education data governance            | YES        |
| Enterprise AI governance obligations | YES        |

## Overall compliance risk

TRUNG BÌNH → GẦN CAO

## Vì sao?

Không phải vì VoiceFirst AI trực tiếp thay giáo viên ra quyết định,
mà vì:

* xử lý voice data
* tích hợp LMS
* truy cập classroom workflow
* có khả năng truy cập dữ liệu học sinh
* có automation trong giáo dục
* có cross-border AI processing
* có audit & accountability requirement

Nguồn tham khảo gốc từ tài liệu TrustLayer AI đã được chuyển đổi cho VoiceFirst AI. fileciteturn0file0
