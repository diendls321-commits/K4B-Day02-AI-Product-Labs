# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên:
- Mã học viên:
- Vai trò / bối cảnh (VD: sinh viên năm X, intern PM, ...):
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem):

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | AI có thể tốt hơn | Tìm lại quyết định/hướng dẫn cũ trong Discord/Slack vì công cụ search mặc định không hiểu bối cảnh. | Sinh viên chạy project, nhân viên mới | Mất 15-20 phút lướt đọc thread cũ; phải tag hỏi lại mentor/quản lý 2-3 lần/tuần. |
| 2 | Tốn thời gian, Pain từ người khác | Gom nhặt ý kiến rải rác trong group chat (ai rảnh lúc nào, thích ăn gì) để chốt lịch trình/địa điểm cho nhóm. | Người đứng ra tổ chức (Organizer, Nhóm trưởng) | Tốn 1-2 tiếng lập poll và Excel; tin nhắn trôi dạt, thành viên phàn nàn chốt lịch quá lâu. |
| 3 | Tốn thời gian, AI có thể tốt hơn | Xâu chuỗi bối cảnh cho task mới vì yêu cầu nằm rải rác chéo nhau ở Jira, Notion và Slack. | Junior Dev, Designer | Mất 30-45 phút đọc dò lại từ đầu trước khi làm; có trung bình 1-2 bug/tháng do đọc sót yêu cầu. |
| 4 | Lặp lại, Pain từ người khác | User báo lỗi nhưng thiếu thông tin nền (thiết bị, OS, version), phải hỏi đi hỏi lại theo một kịch bản cũ. | Customer Support, Developer | 70% ticket mới cần 2-3 lượt ping-pong tin nhắn; mất trung bình 24h chỉ để gom đủ thông tin. |
| 5 | Tốn thời gian | Đối chiếu bài nộp/báo cáo dài so với rubric (tiêu chí) hoặc checklist chuẩn để đảm bảo không thiếu field nào. | Sinh viên, PM | Dành 45-60 phút cuối trước deadline chỉ để scroll lên xuống đối chiếu chéo file Docs dài 20 trang. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**
- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — [Tên problem]

```text
Problem 1 câu:
Junior Dev/Designer mất 30-45 phút lướt tìm và xâu chuỗi thông tin rải rác giữa Jira, Notion, Slack khi nhận task mới, dễ dẫn đến hiểu sai yêu cầu.

Actor:
Junior Developer, Designer (Người trực tiếp thực thi task).

Thời điểm / bối cảnh:
Lúc bắt đầu sprint hoặc khi vừa được assign một ticket mới.

Current workflow 3-7 bước:
1. Đọc mô tả ngắn trên Jira ticket.
2. Tìm link PRD/Spec liên quan trên Notion để đọc chi tiết.
3. Search từ khóa trên Slack xem có thay đổi/decision nào phút chót không.
4. Tự tổng hợp lại thành list to-do cá nhân.
5. Bắt đầu code/design.

Bottleneck:
Bước 2 & 3 — Phải "khảo cổ" qua nhiều nền tảng, đọc luồng tin nhắn dài để lọc ra quyết định cuối cùng.

Impact:
Tốn 30-45 phút chuẩn bị cho mỗi task. Phát sinh 1-2 bug/tháng do đọc sót thay đổi trong thread Slack.

Success metric:
Giảm thời gian nắm bối cảnh xuống dưới 10 phút/task; 0 bug liên quan đến việc "thiếu bối cảnh nền".

Non-AI alternative:
Bắt buộc PM/PO phải cập nhật mọi thay đổi cuối cùng thẳng vào Jira (khó thực thi vì con người hay quên hoặc bận).

AI hypothesis:
Script tự gom link từ Jira/Notion/Slack thread → AI đọc, đối chiếu và sinh ra một "Task Context Summary" (Bản tóm tắt bối cảnh) → Dev đọc và bắt đầu làm.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 45 phút

[1. Đọc Jira ticket: 5']
→ [2. Mở đọc Notion PRD: 15']  <-- bottleneck
→ [3. Search Slack thread: 15'] <-- bottleneck
→ [4. Gom thành to-do list: 10']
→ [5. Bắt đầu làm]

FUTURE STATE — 12 phút

[1. Rule: Tự động gom text/link từ Jira vào prompt: 1']
→ [2. AI đối chiếu Notion/Slack sinh Task Summary: 1']
→ [3. Dev đọc review, đối chiếu chéo nếu thấy lạ: 10'] <-- human boundary
→ [4. Bắt đầu làm]

Fallback: AI tóm tắt thiếu logic → Dev tự click vào link gốc để đọc thủ công như cũ.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — [Tên problem]

```text
Problem 1 câu:
Người viết phải dành 45-60 phút mỏi mắt đối chiếu bản draft dài 20 trang với bảng rubric/checklist để kiểm tra sót ý trước khi nộp.

Actor:
Sinh viên làm assignment, PM viết tài liệu báo cáo.

Thời điểm / bối cảnh:
Giai đoạn hoàn thiện cuối cùng (final review) trước khi nộp hoặc gửi đi.

Current workflow 3-7 bước:
1. Mở file draft (Docs) ở màn hình trái.
2. Mở file Rubric/Checklist ở màn hình phải.
3. Đọc từng mục yêu cầu bên Rubric.
4. Lướt/Ctrl+F tìm ý tương ứng trong draft để check "Đạt/Chưa đạt".
5. Note lại những phần thiếu.
6. Viết bổ sung và chốt nộp.

Bottleneck:
Bước 4 & 5 — Việc đối chiếu chéo ngữ nghĩa (chứ không chỉ keyword) giữa 2 file dài cực kỳ mỏi mệt và dễ bỏ sót do kiệt sức (fatigue).

Impact:
Tốn 45-60 phút soát lỗi cơ học; dễ bị trừ điểm oan hoặc sếp trả về do thiếu các trường thông tin cơ bản.

Success metric:
Giảm thời gian soát lỗi xuống 15 phút; bản nộp pass 100% các mục mandatory (bắt buộc) của rubric.

Non-AI alternative:
Nhờ đồng nghiệp/bạn bè đọc chéo (peer-review) giùm (tốn nguồn lực của người khác, phải chờ đợi).

AI hypothesis:
User cung cấp Draft và Rubric → AI đọc và map nội dung, tick các mục đã có, highlight/quote chính xác chỗ còn thiếu → User tự viết thêm.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 60 phút

[1. Chuẩn bị 2 file Docs & Rubric: 2']
→ [2. Đọc từng mục Rubric: 5']
→ [3. Lướt file Docs để map thông tin: 30'] <-- bottleneck
→ [4. Note phần thiếu: 8'] <-- bottleneck
→ [5. Tự viết bổ sung: 15']

FUTURE STATE — 22 phút

[1. Upload 2 file lên hệ thống: 1']
→ [2. AI map dữ liệu & tick Checklist: 1']
→ [3. AI list các điểm missing: 1']
→ [4. Người review lại kết quả AI bắt lỗi: 4'] <-- human boundary
→ [5. Tự viết bổ sung chỗ thiếu: 15']

Fallback: AI bắt lỗi sai/ảo (hallucination) → Người tự dò lại file Docs như hiện tại. 
Bottleneck mới: User phải đánh giá xem AI bắt lỗi có đúng không.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — [Tên problem]

```text
Problem 1 câu:
Customer Support phải nhắn tin ping-pong 2-3 lượt mới lấy đủ cấu hình máy/version từ user báo lỗi trước khi chuyển cho team Dev xử lý.

Actor:
Customer Support (CS), IT Helpdesk.

Thời điểm / bối cảnh:
Khi nhận được ticket báo lỗi mới (bug report) từ người dùng.

Current workflow 3-7 bước:
1. Đọc ticket phàn nàn của user.
2. Nhận ra thiếu thông tin (version app, hệ điều hành).
3. Dùng template reply xin thêm thông tin.
4. Đợi user trả lời (thường trôi qua ngày).
5. Tổng hợp đủ thông tin vào form chuẩn.
6. Chuyển ticket cho team Dev.

Bottleneck:
Bước 2, 3, 4 — Nhận diện thông tin khuyết và quá trình chờ đợi ping-pong tốn thời gian rác.

Impact:
Kéo dài thời gian xử lý (SLA) lên 24-48h; 70% công việc của CS lúc đầu chỉ là "hỏi han cơ học".

Success metric:
Giảm số lượt ping-pong lấy thông tin trung bình từ 2.5 lượt xuống 0.5 lượt; giảm thời gian chuyển ticket cho Dev (Lead time) xuống 60%.

Non-AI alternative:
Ép user phải điền form dài với các trường bắt buộc (mandatory) ngay từ đầu (dễ làm user bực, bỏ gửi ticket).

AI hypothesis:
AI đọc mô tả ban đầu của user → Bóc tách xem đã có trường nào, thiếu trường nào → Tự draft email hỏi ĐÚNG những chỗ khuyết → CS review rồi gửi.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 24h SLA, 20 phút active work

[1. Đọc ticket ban đầu: 5']
→ [2. Tìm template phù hợp xin thêm info: 5'] <-- bottleneck
→ [3. Gửi email & Đợi: 24h] <-- bottleneck
→ [4. Nhận lại đủ info, copy vào ticket: 10']
→ [5. Assign Dev]

FUTURE STATE — 4h SLA, 7 phút active work

[1. AI tự trigger khi có ticket mới: 0']
→ [2. AI phân tích thiếu sót & draft reply: 1']
→ [3. CS check draft và ấn gửi: 2'] <-- human boundary
→ [4. Đợi (form link động giúp user điền lẹ hơn): 4h]
→ [5. Tự update vào ticket, CS review & Assign Dev: 4']

Fallback: AI bóc tách sai tình trạng lỗi ban đầu → CS vứt draft, tự đọc ticket và gửi template thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```Đối chiếu chéo bản draft (báo cáo, assignment) với Rubric/Checklist để tìm các trường thông tin bị bỏ sót trước khi nộp.

```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```Bài toán này có workflow vô cùng tuyến tính (nhập 2 file → AI đối chiếu chéo → list điểm thiếu → người tự viết bù) và biên giới con người (human boundary) cực kỳ an toàn vì AI chỉ đóng vai trò "mắt dò lỗi", người vẫn quyết định nội dung cuối. Số đo thành công rất dễ lượng hóa: giảm thời gian rà soát thủ công từ 60 phút xuống dưới 20 phút. Impact mang lại lớn vì nó giải quyết đúng nỗi đau sai sót cơ học do "fatigue" (kiệt sức phút chót) trước deadline.

```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```Nếu bản draft sử dụng văn phong lắt léo, ẩn dụ hoặc không chứa các "keyword" y hệt như trong rubric, liệu AI có bắt lỗi sai (báo thiếu dù thực ra có) khiến người dùng bực bội và tốn thời gian check lại từ đầu không?

```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: AI có thể bị đánh lừa bởi việc tài liệu có chứa "từ khóa" nhưng nội dung viết lại rất hời hợt, dẫn đến việc AI đánh dấu "Đạt" nhưng bản chất lại là "Chưa đạt" về mặt chiều sâu.
- Tôi sửa gì: Thu hẹp lại "Success metric" và ranh giới. Xác định rõ định vị: AI chỉ dùng để check tính ĐẦY ĐỦ (Completeness - có làm phần này hay không), tuyệt đối không dùng AI để chấm điểm CHẤT LƯỢNG (Quality - làm tốt hay tệ). Trách nhiệm đánh giá chất lượng vẫn thuộc về người dùng.

### Self-check nộp phần 01
- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
